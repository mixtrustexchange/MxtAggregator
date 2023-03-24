# MixTrust(MXT)

MixTrust(MXT) is a decentralized synthetic asset issuance protocol based on Ethereum, and provides a decentralized cross-chain trading platform for synthetic assets.

## Project Introduction

This repository contains the smart contract code and the trading application code of MixTrust(MXT).

- mixtrust: smart contract code, written in Solidity language.

- exchange: trading application code, written in Vue framework.

## Installation and Running

### Smart Contract

To run the smart contract code, you need to install [Truffle](https://www.trufflesuite.com/) and [Ganache](https://www.trufflesuite.com/ganache).

First, clone this repository to your local machine:

```bash

git clone https://github.com/mixtrustexchange/MxtAggregator.git

```

Then, enter the mixtrust directory, and install dependencies:

```bash

cd mixtrust

npm install

```

Next, start Ganache, and deploy the smart contracts:

```bash

truffle migrate

```

Finally, run the tests:

```bash

truffle test

```

### Trading Application

To run the trading application code, you need to install [Node.js](https://nodejs.org/) and [npm](https://www.npmjs.com/).

First, enter the exchange directory, and install dependencies:

```bash

cd exchange

npm install

```

Then, start the development server:

```bash

npm run serve

```

Finally, visit http://localhost:8080/ in your browser to see the trading application interface.

## Contact Us

If you have any questions or suggestions, please contact us:

- Twitter: [@MixtrustMXT](https://twitter.com/MixtrustMXT)

- Email: mxt@mixtrust.exchange

## License

This project is licensed under the [MIT License](https://github.com/mixtrustexchange/MxtAggregator/blob/master/LICENSE).

