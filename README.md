# Welcome

Welcome to the technical documentation site for the Celo project!

In this documentation you’ll find information on:

- An [overview](docs/overview.md) of the high-level architecture of Celo
- Tutorials to get you started with the [Celo SDK](docs/developer-resources/start.md) and the [Celo networks](docs/getting-started/choosing-a-network.md)
- Reference documentation about the [Celo protocol](docs/celo-codebase/protocol/) and [wallet](docs/celo-codebase/wallet/)
- How to make technical [contributions](docs/community/contributing.md) to the project and community

## Quick Reference

- CELO Owners
  - [Start here](docs/celo-holder-guide/quick-start.md) to find out how to access your account and earn rewards for participating in the network.
- Validator & Node Operators
  - Check out the [Validator overview page](docs/validator-guide/overview.md).
  - Consider running a node on the [Baklava testnet](docs/getting-started/baklava-testnet.md) before getting started on Mainnet.
  - Learn more about running nodes on [Mainnet](docs/getting-started/mainnet.md).
- Developers
  - Start at the [developer tools page](docs/developer-resources/overview.md) for help building a DApp or service on the Celo network.
- Integration Guide
  - [This section](docs/developer-resources/integrations/integrations.md) includes guides on common ways for integrating Celo into your service. This may be relevant for custodians, exchanges or other services that intend to custody Celo assets like CELO and cUSD.

### About Celo

Celo’s purpose is to empower anyone with a smartphone anywhere in the world to have access to financial services, send money to phone numbers, and pay merchants.

The project aims to be a decentralized platform that is not controlled by any single entity, but instead developed, upgraded and operated by a broad community of individuals, organizations and partners.

Uniquely, Celo is oriented around providing the simplest possible experience for end users, who may have no familiarity with cryptocurrencies, and may be using low cost devices with limited connectivity. To achieve this, the project takes a full-stack approach, comprising of both a protocol and applications that use that protocol.

The Celo protocol is an open, distributed cryptographic protocol that allows applications to make transactions with and perform computation on a family of cryptocurrencies, including ones pegged to ‘fiat’ currencies like the US Dollar. The [Celo Wallet](http://celo.org/build/wallet) app, the first of an ecosystem of applications, allows end users to manage accounts and make payments securely and simply by taking advantage of the innovations in the Celo protocol.

Highlights include:

- **Stable Value Currencies**

  Celo includes native support for multiple ERC20-like stable currencies pegged to ‘fiat’ currencies like the US dollar, to facilitate the use of Celo as a means of payment.

- **Accounts Linked to Phone Numbers**

  Celo maintains a secure decentralized mapping of phone numbers that allow wallet users to send and receive payments with their existing contacts simply and with confidence that the payment will reach the intended recipient.

- **Transaction Fees in Any Currency**

  Users can pay transaction fees in stable currencies, so that they do not need to manage balances of different currencies.

- **Immediate Syncing Even on Slow Connections**

  Extremely fast, secure synchronization between mobile devices and the Celo network means that even wallet users with high latency, low bandwidth, or high cost data tariffs can use Celo. Celo removes the need to check every header before a received header can be trusted. Performance will be further improved with BLS signature aggregation and succinct zero-knowledge proofs, via zk-SNARKs.

- **Proof-of-Stake**

  Celo uses a proof-of-stake consensus algorithm. In comparison to Proof of Work systems like Bitcoin and Ethereum, this eliminates the negative environmental impact and means that users can make transactions that are cheaper, faster, and where the outcome cannot be changed once complete.

- **Full Node Incentives**

  The Celo protocol offers incentives for running full nodes to service the light clients that run on each mobile device. Unlike other proof-of-stake systems, users can still earn cryptocurrency in exchange for providing compute resources without having to stake funds.

- **On-chain Governance**

  Since great user experiences need constant iteration, Celo supports rapid upgrades and protocol changes via on-chain governance in which all cryptocurrency holders can participate.

- **Programmable \(Full EVM Compatibility\)**

  Celo includes a programmable smart contract platform that is compatible with the Ethereum Virtual Machine, which is already widely adopted, familiar to developers, and has strong tool support. This enables Celo to deliver rich user features and rapidly support a wide ecosystem of third-party applications and extensions.

- **Self Custody**

  Users have access to and fully control their funds and account keys, and don't need to depend on third parties to make payments.

### Current Status

The Celo project is live on [Mainnet](https://medium.com/celoorg/its-official-celo-mainnet-is-here-6a3a71763f68)!

The code is entirely open source and available on [GitHub](https://github.com/celo-org). Versions of all the major components of both the protocol and wallet exist, but the platform as a whole is under active development and testing by the Celo community.

The [Alfajores Testnet](docs/getting-started/alfajores-testnet.md) is the first of several networks designed for testing and for developers to experiment and learn more about Celo. You can set up an account, receive funds, and try out the Celo Wallet and Celo CLI. [Get started here](docs/getting-started/faucet.md).

{% hint style="warning" %}
The Alfajores Testnet’s tokens hold no real world economic value. The entirety of the testnet’s data will be reset on a regular basis. This will erase your accounts, their balance and your transaction history. Your use of the Alfajores Tesnet is subject to the [Alfajores Testnet Disclaimer](docs/important-information/alfajores-testnet-disclaimer.md).
{% endhint %}

The [Baklava Testnet](docs/getting-started/baklava-testnet.md) is the second Celo test network after Alfajores. You can use it to participate in the The Great Celo Stake Off. Subject to these Terms and Conditions, eligible participants will have the opportunity to receive CELO at the Mainnet launch of the Celo Protocol. The Stake Off will operate in phases, with each phase focusing on a different part of the protocol or infrastructure to test.

The Celo community's work is focused on the path to a production Celo network that holds economic value. This means testing, running security audits, and building broader involvement around a longer-term roadmap. The project also continues to remain focused on user experience.

The team working on Celo anticipates working to improve and expand the range of APIs available for developers to use in creating extensions to Celo, whether as smart contracts or applications. Your input is very welcome in the form of use cases, suggestions, and bug reports.

{% hint style="warning" %}
While development proceeds, Celo’s protocol and its APIs will evolve and any smart contracts or applications built to operate on Alfajores or with respect to the current codebase may become incompatible.
{% endhint %}

Celo is a project with a mission of financial inclusion that consists entirely of open source code, is deployed as an open, decentralized runtime, and promotes open governance. Make it your project too. Please [get involved](docs/community/contributing.md)!

### Useful Links <a id="useful-links"></a>

Learn more about Celo:

- [Overview of Celo’s architecture ](docs/overview.md)
- [Technical blog posts](https://medium.com/celoorg/technology/home)

Browse the code, raise an issue, or contribute a PR:

- [Monorepo GitHub Page](https://github.com/celo-org/celo-monorepo)
- [Celo Client GitHub Page](https://github.com/celo-org/celo-blockchain)
- [Contributing Guide](docs/community/contributing.md)
- [Celo Build Page](https://celo.org/build)

Try Celo out:

- [Using the Mobile Wallet](docs/getting-started/using-the-mobile-wallet.md) on the Alfajores Testnet
- [Introduction to the CLI ](docs/command-line-interface/introduction.md)on the Alfajores Testnet

Read the Whitepapers:

- [Main Celo Whitepaper](https://celo.org/papers/whitepaper) and [introductory blog post](https://medium.com/celohq/a-look-at-the-celo-whitepaper-c0061118ffd4)
- [Stability Analysis Whitepaper](https://celo.org/papers/Celo_Stability_Analysis.pdf) and [blog post](https://medium.com/celohq/a-look-at-the-celo-stability-analysis-white-paper-part-1-23edd5ef8b5)
- [BFTree \(Longer Term Consensus Plan\)](https://storage.googleapis.com/celo_whitepapers/BFTree%20-%20Scaling%20HotStuff%20to%20Millions%20of%20Validators.pdf)

Alfajores Testnet links:

- [Alfajores Testnet Faucet](https://celo.org/build/faucet) - get testnet tokens to experiment with
- [Celo Wallet for Alfajores](https://celo.org/build/wallet) - download the Android wallet app for the testnet from the Play Store
- [Alfajores Testnet Network Status](https://alfajores-celostats.celo-testnet.org) - to check the current availability of the testnet
- [Alfajores Testnet Block Explorer](https://alfajores-blockscout.celo-testnet.org) - explore the history of the blockchain and view transaction details

Ask questions, find answers, and get in touch:

- [Celo Forum](https://forum.celo.org)
- [Celo Developer Chat on Discord](https://chat.celo.org)
- [Celo Subreddit](https://www.reddit.com/r/celo/)
- [Celo Website](https://celo.org/build)
- [Host a Meetup](https://airtable.com/shrTCM7LddTxOm3r6)

### Notes <a id="notes"></a>

If you are viewing this document on GitHub, please visit the [official hosted version](https://docs.celo.org) of this content for a better experience. Additionally, Celo is in active development. If you encounter any issues or bugs or have suggestions for how Celo can improve, please post an issue or pull request [here](https://github.com/celo-org/celo-monorepo).

***

# Building the Website

This website is built using [Docusaurus 2](https://v2.docusaurus.io/), a modern static website generator.

## Installation

```console
yarn install
```

## Local Development

```console
yarn start
```

This command starts a local development server and open up a browser window. Most changes are reflected live without having to restart the server.

## Build

```console
yarn build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

## Deployment

```console
GIT_USER=<Your GitHub username> USE_SSH=true yarn deploy
```

If you are using GitHub pages for hosting, this command is a convenient way to build the website and push to the `gh-pages` branch.
