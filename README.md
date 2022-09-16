# HackBoston Project Ideas

Hackathon participants are free to explore and build projects that span a variety of DeFi use cases.** The following is a list of interesting possible ideas sourced from the Telos community and the participating judges/speakers. One of the beauties of utilizing DeFi’s composable building blocks is that they can be remixed and modified to build entirely new financial services. So take a look if you or your team is in need of some inspiration! 

* Stableswap pool AMM
* Yield Optimizer similiar to Beefy, Pickle, Yearn
* Streaming Payments platform for subscriptions using NFTs to verify
* Central limit order book DEX similar to [Serum](https://www.projectserum.com/)
* Lending front end and primitive: Money market lending protocol EVM native (akin to Compound or Aave)
* Cross-Chain Lending: A lending protocol that immediately provides liquidity for assets transferred cross-chain, utilizing the Wormhole bridge - such that users don't need to wait for the cross-chain assets to be fully confirmed on both chains - in return for a fee
* Fixed-Rate Loans: Where users can take out a fixed-rate loan on an Ethereum Lending/Borrowing protocol that is enabled by an on-chain interest rate swap order book on [OmniDex](https://omnidex.finance/) or [Zappy Finance](https://www.zappy.finance/liquidity/pool?main=0x9a271e3748f59222f5581bae2540daa5806b3f77&base=tlos)
* Censorship resistant Wallstreetbets
* Basis Trade Stablecoin
* Make use of Coingecko API in Telos dapps: https://www.coingecko.com/en/api
* Liquidation bot for undercollateralized positions
* Reinsurance markets: An expansion yInsure
* On-chain subscriptions: A protocol that is a factory for any app to create on-chain payment streaming and subscriptions. Combine elements like NFTs to increase engagement and unlock features
* Analytics: perhaps the aggregator above can also roll in key on-chain KPIs that tell you if you’re going to swap token A then what % of buy vs. sell orders and sentiment in the past [24] hrs, whale movements, project developments etc.
- Education- a game-type protocol that walks a user thu the DeFi journey. Combining video clips, resources and yield-farming/NFT quest type journey to get normies up to speed
* DeFi asset manager: A single interface consolidating all DeFi assets and liabilities across different platforms (and different chains) into one.
* DEX Aggregator: A cross-chain DEX aggregator that allows users to choose the best price for execution across multiple DeFi platforms, including cross-chain platforms.
* Build-your-own Liquidity Mining platform: Utilize yield farming to jumpstart your product
* Prediction market minter with DIA Oracle integration
* Fee Compare: A simple interface that tracks and compares cost to execute something given certain parameters across various DeFi platforms. Parameters include desired spread, transaction fees, trading pair set. Can also track total value saved in transaction fees/spread
* Slashing Insurance: A simple insurance protocol where the community can provide insurance for validators against the risk of being slashed
* Smart Contract Insurance: Something akin to Nexus Mutual
* DeFi visualization dashboards: Plugging into and displaying data from Hyperion, teloscan.io, Telos RPC API. 
* Security audits of existing Telos infrastructure
* Build a simple oracle that allows Telos Dapps to connect to an off-chain API or Websocket (e.g. a price feed)

# Swap, Borrow/lend, and Margin Implementation Ideas

Ideas to extend existing source-code (token-swap, token-lending)

* Add support for new token-swap curve that’s using DIA as oracle
* Add support for cross-asset collateral to token-lending.
* Single collateral token for all deposits can be used across loans
* Add support for adding/removing collateral from token-lending obligation (top-up collateral)
* Add support for liquidations using ordered heap: Liquidator will be only to liquidate positions with lowest health score first
* Add support for token-swap LP as collateral to token-lending. Use-case: single token exposure in AMM
* Add support to token-lending for stable borrowing rates
* Margin trading using token-lending: User can initiate (short/long) margin trade with predefined max leverage 
* Token lending stores position in escrow


---------- 

