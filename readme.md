**Digital Currencies Overview**
*   **Digital currency** is a broad term for anything representing value digitally.
*   **Digital currencies** include cryptocurrencies, central bank digital currencies (CBDCs), stablecoins, and virtual currencies.
*   The course focuses on **Distributed Ledger Technology (DLT)** based digital currency.
*   **DLT** is a digital system that records and shares information across a network of computers, eliminating the need for a central authority.

**Types of Digital Currencies**
*   **Cryptocurrencies:** Use cryptographic encryption techniques and a decentralized ledger (blockchain) for verification. They offer decentralization and anonymity but can be volatile and susceptible to price manipulation.
*   **CBDCs:** Digital currencies issued by central banks.
*   **Stablecoins:** Designed to maintain a stable value relative to a traditional currency or asset, often backed by reserves or algorithms.
*   **Virtual Currencies:** Unregulated digital currency used in virtual worlds or online gaming environments.

**Digital Currency Ecosystem**
*   **Key players** include miners/stakers, developers, crypto exchanges, and media platforms.
*   **Bitcoin (BTC)** is the most active crypto ecosystem.
*   **Binance Smart Chain (BSC)** is the fastest-growing ecosystem.
*   **Ethereum** is also considered an ecosystem with its blockchain, Ether (ETH), smart contracts, dApps, wallets, and developer tools.

**Key Differences Among Digital Currencies**

| Criteria             | Cryptocurrency           | CBDCs                    | Stablecoins                | Virtual Currencies        |
| -------------------- | ------------------------ | ------------------------ | -------------------------- | ------------------------- |
| Control/Issuance     | Decentralized            | Centralized/Decentralized | Decentralized              | Centralized/Decentralized |
| Regulation           | Little to none           | Regulated                | Some regulatory scrutiny | Little to none          |
| Value Stability      | Highly volatile          | Stable                   | Designed to be stable    | May vary                |
| Underlying Asset     | None                     | Government-backed        | Tied to an underlying asset | May vary                |
| Privacy/Anonymity    | High                     | Limited                  | May vary                   | May vary                |
| Transaction Processing | May be slow              | Fast                     | Fast                       | Fast                      |
| Fees                 | Vary                     | Low to none              | Vary                       | Low to moderate           |

**Programming for Smart Contracts**
*   **Coins** operate on their own blockchain and are used as a payment method.
*   **Tokens** are built on existing blockchains and offer a wider range of functionalities.
*   Creating a **coin** requires building a new blockchain. **Tokens** are issued via smart contracts.

**Fungible vs. Non-Fungible Tokens**

| Feature          | Fungible Tokens                     | Nonfungible Tokens (NFTs)        |
| ---------------- | ----------------------------------- | -------------------------------- |
| Main Features    | Divisible, Non-unique, Interchangeable | Indivisible, Unique, Irreplaceable |
| Real-World Purposes | Payment system, Store of value          | Intellectual property, Artwork     |
| Standards        | ERC-20                              | ERC-721                          |
| Content Stored   | Value                               | Data                             |

*   **ERC-20** is a standard for fungible tokens, enabling interoperability and widespread use.
*   **Fungible tokens** are interchangeable and have the same value. Examples: USD Coin (USDC), Ether (ETH).
*   **Non-fungible tokens (NFTs)** are unique and non-interchangeable.
*   **Utility tokens** provide access to a product or service. Example: yPredict (YPRED).
*   **Security tokens** represent ownership in an asset or company.
*   **Wrapped Bitcoin (WBTC)** brings Bitcoin's liquidity to the Ethereum blockchain.

**ERC-20 Key Functions**
*   `totalSupply()`: Checks the total number of tokens.
*   `balanceOf(owner)`: Checks the balance for an account.
*   `transfer(to, value)`: Transfers tokens from the owner to another account.
*   `transferFrom(from, to, value)`: Sends tokens authorized from one address to another.
*   `approve(spender, value)`: Allows spender to withdraw from one's account.
*   `allowance(owner, spender)`: Checks how many tokens can be called by permission.

**Solidity**
*   **Solidity** is a high-level, contract-oriented programming language for writing smart contracts on Ethereum.
*   A **contract** is a collection of code (functions) and data (state) that resides at a specific address on the Ethereum blockchain.
*   Example of a simple contract with functions to set and get a stored data value.
*   **Subcurrency Example**: A basic cryptocurrency implementation where only the contract creator can mint new coins, and anyone can send coins to each other.

**Hardhat**
*   **Hardhat** is a development environment for building on Ethereum, managing tasks, and automating processes.
*   It includes Hardhat Network, a local Ethereum network for deploying contracts, running tests, and debugging code.

**ERC-20 Token Deployment with Hardhat**
*   Involves creating sample contracts, tests, and deployment instructions for Ethereum test networks like Sepolia.

**Time Series Analysis**
*   **Time series analysis** is used to identify patterns, dependencies, and anomalies in cryptocurrency data.
*   **Correlogram (Sample ACF)** is used to graphically check whether serial dependence exists at a particular lag.
*   **Augmented Dickey-Fuller (ADF) test** is used to test for a unit root.

**Primer on DLT, Blockchain, Cryptocurrencies, and Cryptographic Tools**
*   **Distributed Ledger (DL):** A database synchronized and accessible across different sites by multiple participants.
*   **Distributed Ledger Technology (DLT):** The technological infrastructure and protocols that allow simultaneous access, validation, and record updating.
*   **Blockchain:** A special type of DLT where records (blocks) of transactions are maintained across computers in a peer-to-peer network.
*   **Centralized vs. Decentralized Networks:** Centralized networks rely on central servers, while decentralized networks (peer-to-peer) distribute roles across nodes.
*   **Digital Identity (DI):** Involves secret (private) and public keys for secure identification and authorization.
*   **Double Spending (DS):** Preventing users from spending the same digital currency twice.
*   **Sybil Attacks:** A network participant creates multiple pseudonymous identities to manipulate the network. Proof-of-Work (PoW) helps deter these attacks.
*   **Blockchain Network (BNW):** Nodes maintain a dynamic view of the blockchain, validating and relaying transactions.
*   **Forks:** Occur when two or more valid blocks refer to the same parent, potentially due to attacks or simultaneous solutions by miners.
*   **Cryptography:** Involves hidden writing, ciphertext, and keys for secure communication.
*   **Symmetric Key Cryptography (SKC):** The same key is used for encryption and decryption.
*   **Asymmetric Key Cryptography (AKC):** Different keys are used for encryption and decryption.
*   **Hash Functions (HFs):** Easy to compute but difficult to find a preimage for.
*   **Quantum-Resistant Cryptography:** Algorithms designed to be secure against quantum computer attacks.

**Bitcoin, Ethereum, and Ripple**
*   **Bitcoin (BTC):** The first major cryptocurrency, designed for decentralized transactions.
*   **Ethereum (ETH):** A platform for executing smart contracts and building decentralized applications (dApps).
*   **Ripple (XRP):** A cryptocurrency that does not use conventional mechanisms like block creation or proof-of-work.
*   **Bitcoin Addresses:** Unique identifiers for sending and receiving Bitcoin.
*   **Bitcoin Transactions:** Move unspent transaction outputs (UTXO) to the next transaction.
*   **Bitcoin Mining Difficulty:** Adjusted every 2,016 blocks to maintain a 10-minute block time.
*   **Ethereum Smart Contracts:** Computer code that executes deterministic commands upon receiving legally relevant inputs.
*   **Ripple:** Uses pre-minted XRP tokens and a Unique Node List (UNL) for consensus.
