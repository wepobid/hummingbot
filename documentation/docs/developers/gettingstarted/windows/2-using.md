# Developer Quickstart – Windows | Using Hummingbot

## 1. What you'll need to start:

### Crypto Inventory

**Why this is needed**: In order to run trading bot, you'll need some inventory of crypto assets available on the exchange, or in your Ethereum wallet (for Ethereum-based decentralized exchanges).

Remember that you need inventory of both the **base asset** (the asset that you are buying and selling) and the **quote asset** (the asset that you exchange for it). For example, if you are making a market in a `BTC/USDT` trading pair, you'll need some `BTC` and `USDT`.

In addition, be aware of the minimum order size requirements on different exchanges. For more information, please see [Connectors](/connectors).

### API Keys

**Why this is needed**: In order to run a bot on a centralized exchange like Binance, you will need to enter the exchange API keys during the Hummingbot configuration process.

For more information on how to get the API keys for each exchange, please see [API Keys](/installation/api-keys).

### Ethereum Wallet

**Why this is needed**: In order to earn rewards from Liquidity Bounties, you need an Ethereum wallet. In addition, you'll need to import an Ethereum wallet when you run a trading bot on an Ethereum-based decentralized exchange.

For more information on creating or importing an Ethereum wallet, see [Ethereum wallet](/installation/wallet).

### Ethereum Node (DEX only)
**Why this is needed**: When you run a trading bot on a Ethereum-based decentralized exchange, your wallet sends signed transactions to the blockchain via an Ethereum node.

For more information, see [Ethereum node](/installation/node/node). To get a free node, see [Get a Free Ethereum Node](/installation/node/infura/).

## 2. Using Hummingbot

### Relevant User Manual Links

- [Using the Client](/operation/client)
- [Configuring Hummingbot](/operation/configuration)
- [Running Trading Bots](/operation/running-bots)

---
# Next: [Re-compiling Hummingbot for a Code Change](/developers/gettingstarted/windows/3-recompiling)