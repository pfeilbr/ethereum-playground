## [Ethereum](https://www.ethereum.org/) Playground

learn and experiment with [Ethereum](https://www.ethereum.org/) decentralized blockchain based platform

## TODO

* walk all the testnet transaction and get counts of the addresses to see which addresses produce the most transactions
* walk all testnet transactions and plot transaction count over time for the top X% of addresses that produce the most transactions

## Files and Directories of Interest

**Production**

```sh
~/Library/Ethereum
~/Library/Ethereum/geth/chaindata
```

**TEST-NET**

```sh
~/Library/Ethereum/testnet
~/Library/Ethereum/testnet/geth/chaindata
```

## Ethereum Wallet

Ethereum Wallet Screenshot

![](http://static-screenshots-01.s3-website-us-east-1.amazonaws.com/Ethereum_Wallet_1E2DB8EC.png)

## [Geth](https://github.com/ethereum/go-ethereum/wiki/geth) CLI

command line interface for running a full ethereum node

```sh
# attach to existing geth instance (e.g. Ethereum Wallet GUI app's geth instance). opens up a javascript repl
geth attach

# js console
geth console

# open testnet console
geth --testnet console
```

## Ethereum Block Explorer

* production - <https://etherscan.io/>
* testnet - <https://testnet.etherscan.io/>

## [Ethereum Javascript API](https://github.com/ethereum/web3.js)

* [Web3 JavaScript Ðapp API](https://github.com/ethereum/wiki/wiki/JavaScript-API)
* [web3.js](https://github.com/ethereum/web3.js) npm module
