This is really simple demo for how to depploy smart contract to local blockchain

## Using:

- Ethers.js
- Ganache
- solcjs for compilation

## Steps to reproduce:

You need to:

- install ganache,
- start a local blockchain,
- create .env file with rpc url and private key
- or use alchemy.com to connect to a testnet
- `yarn install`
- `yarn run compile`
- `yarn run build`
- `yarn run deploy`

## Note

If you have chainId missmatch error try using 1337, no mather what is written in ganache gui
