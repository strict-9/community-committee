# TrustNote 2.0 Roadmap
Last updated: Sept 19, 2018

[TrustNote](www.trustnote.org) is a rapidly moving, community supported open source project. This document is intended to provide guidance about priorities and focus areas of TrustNote developers, and the functionalities that can be expected in the upcoming releases. Many of these areas are driven by community use cases, and we welcome further contributions to TrustNote.

## Design Goals

### Fast
Transactions in TrustNote are represented "as is" without being grouped into blocks, new transactions are verified immediately by nearby transactions without being put into a queue. This will speed up your transaction performance by getting rid of blocks and queues.

### Scalable
By decoupling double-spend detection from transaction verification and allowing transactions to be verified by nearby transactions in parallel, TrustNote can provide elastic scalability - adding more nodes or transactions, transactions will get verified faster and you will get higher throughput.

### Developer Friendly
TrustNote provides a verifiable, safe, and easy to use smart contract system supporting dynamic languages including non-Turing complete languages, you code in an easy language and straightforward way.

Popular tasks like token issuance, management and mining are provided as a service, no need for coding at all.

## Roadmap

### Mainnet
Start with technical architecture and consensus mechanism optimization, we will further improves performance and security of TrustNote, adding features to enable more use cases.

#### Performance Goal:
To support 5,000 transactions per second in stage 1, and support 20,000 transactions per second in stage 2. This will be achievable by optimizing ledger data storage, unit verification mechanism, main chain stabilizing algorithm etc.

#### New Features:
- Mining Support
- Providing Oracle development kit (including TrustNote Oracle protocol) 
- Further extent TrustNote Smart Contract System’s instruction sets
- Micro-Node Protocol
- Cross-Blockchain Gateway
- Ledger Compression Mechanism
- Other Consensus Mechanisms (TrustNote-BA/DPoS)

#### Timeline:
- TrustNote 2.0 Alpha Release (testnet only) go Live - Sept 2018
- TrustNote 2.0 Consensus Mechanism (TrustME-PoW) and Hard Fork Solution - Oct 2018
- Super Node Program and TrustNote 2.0 Incentivization Program (Beta) – Nov 2018
- TrustNote 2.0 Beta Release (testnet only) go Live – Dec 2018
- Micro Node Protocol – Feb 2019
- TrustNote 2.0 Beta release (testnet only) Open for Public Testing – Feb 2019
- Extended Smart Contract Instruction Sets – Apil 2019
- TrustNote 2.0 Main Net go Live – Q3 2019

### Wallet
To accommodate both quality and speed of development, we decide to support 2 variants of wallet including:

**Official Wallet** – maintained by core developers, focus on providing a smaller set of features but offers a fast, stable, and user-friendly wallet that everyone can use.

**Community Wallet** – maintained by TrustNote developers community, focus on new feature development including:
- Multiple crypto-currencies support
- Wallet SDK
- In-App Browsers (enabling web based blockchain apps and DApps)

#### Timeline:
- Community development plan for Community Wallet – Sept 2018
- Official Wallet New Release – Oct 2018
- Community Wallet Alpha Release – Dec 2018
- Community Wallet Beta Release – April 2019

### Developers Community
Great software is supported by great people, TrustNote is no exception. To make development easier, we will continue to update and providing more SDKs in different languages, we also plan to host a TrustNote Hackathon so developers from the world can participate, and get first hand support in the development of scalable decentralized solutions.

### Services
We are aiming to provide complete solution and services for use cases in IoT, Blockchain Gaming, Social Apps, Fintech, Supply Chain Management etc., more detailed plans will be announced here in the coming months.
