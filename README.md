# Awesome Talent Olympics Projects

> A community curated list of awesome Talent Olympics Projects

## What is Talent Olympics?

The [Talent Olympics](https://earn.superteam.fun/talent-olympics/) is designed to help talented developers from around the world get jobs at the best companies on Solana. To enter, simply complete the developer challenges below. Each challenge has a prize pool for the best submissions, and the participants with the most points globally will split an additional $10,000 prize pool and receive interviews with our hiring partners.

## Contents

- [New Wallet with Swap Functionality](#new-wallet-with-swap-functionality)
- [Escrow UI + Blink](#escrow-ui--blink)
- [Oracle Aggregator](#tooling-data-explorerdashboard)
- [Tooling Data Explorer/Dashboard](#tooling-data-explorerdashboard)
- [Create a Marketplace UI](#create-a-marketplace-ui)
- [NFT Mint, Vault & Swap](#nft-mint-vault--swap)
- [DAO Voting Program](#dao-voting-program)
- [Prediction Market & Blink for Memecoins](#prediction-market--blink-for-memecoins)
- [Whitelist-gated Token Sale](#whitelist-gated-token-sale)
- [Two-sided Marketplace for Services](#two-sided-marketplace-for-services)

## New Wallet with Swap Functionality

<details>
  <summary>Challenge</summary>
  
  ## Part One: Wallet Design and Integration

### Scope of Work

Design and develop a flexible wallet that is both embedded and browser-based. The wallet should seamlessly integrate with a partner’s application and offer full connectivity for testing on platforms such as Cloudflare or Vercel.

---

## Part Two: Swap Functionality

### Scope of Work

Create a wallet that facilitates peer-to-peer (P2P) asset swaps. The wallet should support the swapping of at least four different assets by default and incorporate a pricing mechanism (oracles) to ensure optimal swaps.

### Requirements

- **Asset Support:** Enable P2P swaps for a minimum of four different assets.
- **Pricing Mechanism:** Integrate oracles or a similar mechanism to determine the best swap rates.
- **Deployment:** Ensure the wallet can be tested and deployed on platforms like Cloudflare or Vercel.
</details>

### Submissions

- https://earn.superteam.fun/listing/new-wallet-design-and-swap-functionality-st-talent-olympics/submission/
- https://github.com/yakuppgeyikk96/wallet-ui
- https://github.com/MeremArt/Solana-Swap

## Escrow UI + Blink

<details>
  <summary>Challenge</summary>
  
## Escrow UI Development

### Scope of Work

Design and develop a user interface (UI) for a creative escrow system using [Anchor Escrow] contract. Ensure that the frontend (FE) is fully integrated with the contract and can be tested on platforms like Cloudflare or Vercel. Additionally, create a Blink for the application — this is optional.

### Requirements

- **Escrow UI:** Develop an intuitive and visually appealing interface for the escrow system.
- **Contract Integration:** Ensure seamless connectivity between the escrow contract and the frontend.
- **Testing:** The application should be ready for deployment and testing on Cloudflare or Vercel.

### Optional:

- **Blink Creation:** Develop a Blink for the application to showcase its features.

</details>

### Submissions

- https://earn.superteam.fun/listing/escrow-ui-blink-st-talent-olympics/submission/
- https://github.com/trankhacvy/talent-olympics/tree/main/escrow-ui-blink
- https://github.com/HongThaiPham/talent-olympic-escrow-ui-and-blink
- https://github.com/Manice18/blink-escrow

## Tooling Data Explorer/Dashboard

<details>
  <summary>Challenge</summary>

## Tooling Data Explorer/Dashboard

### Scope of Work

Design and develop an explorer or dashboard that fetches data from RPC and/or API sources. The UI should offer a clear and easy-to-use experience for a broad range of users.

**Requirements:**

- **Data Fetching**: Retrieve data from RPC and/or API endpoints.

- **User Experience**: Create an intuitive and user-friendly interface.

- **Deployment**: Ensure the explorer or dashboard can be tested and deployed on Cloudflare or Vercel.

</details>

### Submissions

- https://earn.superteam.fun/listing/tooling-data-explorerdashboard-st-talent-olympics/submission/
- https://github.com/sekaiking/solsight
- https://github.com/starc007/walletwit

## Oracle Aggregator

<details>
  <summary>Challenge</summary>

## Oracle Aggregator

### Scope of Work

Design and develop an Oracle Aggregator for a DeFi application. The aggregator should pull price feeds from at least two different oracle sources, calculate an average, and display it on the frontend (FE). Note- for this bounty, you MUST use the new Pyth oracle model.

### Requirements:

- **Oracle Integration**: Fetch price feeds from at least two different oracle providers.

- **Data Aggregation**: Compute the average of the fetched price feeds.

- **Frontend Display**: Present the aggregated data on the UI.

- **Deployment**: Ensure the application can be tested and deployed on Cloudflare or Vercel.

</details>

### Submissions

- https://earn.superteam.fun/listing/oracle-aggregator-st-talent-olympics/submission/
- https://github.com/thejustinson/oraculate
- https://github.com/Sait-C/solana-oracle-aggregator

## Create a Marketplace UI

<details>
  <summary>Challenge</summary>

## Create a Marketplace UI

### Scope of Work

Design and develop a creative marketplace UI connected to the provided [Marketplace] contract. Ensure full integration and testing capability on Cloudflare or Vercel. Create a Blink for the application — this is optional.

### Requirements:

- **UI Development**: Design an engaging and user-friendly marketplace interface.

- **Contract Integration**: Integrate the provided Marketplace contract with the UI.

- **Deployment**: Ensure the marketplace can be tested and deployed on Cloudflare or Vercel.

### Optional:

- Blink Creation: Develop a Blink to highlight the marketplace’s features.

</details>

### Submissions

- https://earn.superteam.fun/listing/create-a-marketplace-ui-st-talent-olympics/submission/
- https://github.com/berkaycirak/solana-marketplace-challenge
- https://github.com/trankhacvy/talent-olympics/tree/main/marketplace-ui
- https://github.com/hhdgknsn/anchor-marketplace-basic-ui

## NFT Mint, Vault & Swap

<details>
  <summary>Challenge</summary>

## NFT Minting and Swap Program

### Scope of Work

Develop a program using Anchor that mints a collection of NFTs. Create a vault to lock these NFTs, where the rent for locking is returned to the protocol rather than the user. This project must include storage and retrieval of images with appropriate metadata. Additionally, create a swap program using Native Rust or Anchor that allows users to exchange $SOL for NFTs. This program should perform all necessary checks, use a vault, and enable swapping between $SOL and NFTs. Here's the checklist:

- **Mint a collection of NFTs using Anchor.**
- **Develop a vault system to lock NFTs, where rental fees are returned to the protocol.**
- **Ensure image storage and retrieval are functional and metadata is appropriately assigned.**
- **Create a swap program using Native Rust or Anchor that allows users to exchange $SOL for NFTs.**

</details>

### Submissions

- http://earn.superteam.fun/listing/nft-creation-and-vault-integration-with-anchor-st-talent-olympics/submission/
- https://github.com/dannpl/nftx
- https://github.com/0xGRAV3R/nft-mint-vault-swap
- https://github.com/0xCipherCoder/nft-minter

## DAO Voting Program

<details>
  <summary>Challenge</summary>

## DAO Voting Program

### Scope of Work

Develop a DAO voting program using Anchor. This program should allow users to vote on proposals and display results. Optionally, implement "privacy" voting using Zero-Knowledge (ZK) proofs or verifiable compute. Reward points should be given to users for participation.

- Create a DAO voting system using Anchor.

- Implement a voting system and display the results.

- Optionally, add privacy voting using ZK proofs or verifiable compute.

- Reward points to users for voting participation.

</details>

### Submissions

- https://earn.superteam.fun/listing/dao-voting-program-st-talent-olympics/submission/
- https://github.com/mael-bomane/dao/
- https://github.com/akshatcoder-hash/zk-voting
- https://github.com/ritikbhatt20/Dao_Zk_Proof_Voting

## Prediction Market & Blink for Memecoins

<details>
  <summary>Challenge</summary>

## Prediction Market & Blink for Memecoins

### Scope of Work

Using binary option models, create a prediction market for Solana meme coin prices. Users should be able to predict if a meme coin price will end higher or lower within a specified timeframe.
Additionally, develop a Blink for this program — this is **optional**.

- Develop a prediction market using binary options for Solana meme coins.

- Allow users to enter a meme coin and make price predictions.

- Optional: Create a blink to demonstrate the program.

</details>

### Submissions

- https://earn.superteam.fun/listing/prediction-market-and-blink-for-memecoins-st-talent-olympics/submission/
- https://github.com/NtemKenyor/P_M_-_B_4_Memecoins/
- https://github.com/HongThaiPham/talent-olympics-prediction-merket-and-blink-for-memecoin
- https://github.com/kox/talent-olympics-meme-predictions

## Whitelist-gated Token Sale

<details>
  <summary>Challenge</summary>

## Whitelist-gated Token Sale

### Scope of Work

Develop a program using Native Rust or Anchor to allow users to participate in a whitelist-gated sale for a new token. The token price should be static with a limit per wallet address.

Optional: Develop a Blink for this program.

- Create a whitelist-gated sale program using Native Rust or Anchor.

- Ensure the token price remains static and set a purchase limit per wallet.

- Optional: Create a blink to demonstrate the program.

</details>

### Submissions

- https://earn.superteam.fun/listing/whitelist-gated-token-sale-st-talent-olympics/submission/
- https://github.com/ardata-tech/solana-olympics-2024/tree/main
- https://github.com/cryptoloutre/whitelist-gated-token-sale
- https://github.com/trankhacvy/talent-olympics/tree/main/whitelist-gated-token-sale

## Two-sided Marketplace for Services

<details>

  <summary>Challenge</summary>

## Two-sided Marketplace for Services

### Scope of Work

Using Anchor, create a 2-sided marketplace model for services. Vendors should be able to list services, with service agreements represented by metadata in NFTs. Consumers should be able to purchase service NFTs. The marketplace should support soulbound and non-soulbound NFTs and collect royalties on resales.

- Develop a 2-sided marketplace using Anchor.

- Allow vendors to list services as NFTs.

- Enable consumers to purchase service NFTs.

- Support soulbound and non-soulbound NFTs, with royalty collection for resales.

</details>

### Submissions

- https://earn.superteam.fun/listing/two-sided-marketplace-for-services-st-talent-olympics/submission/
- https://github.com/Memewtoo/nftaas-marketplace
- https://github.com/toanbt173404/two-sided-services-marketplace
- https://github.com/thewuhxyz/talent-olympics
