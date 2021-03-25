# CELO METACOIN

## Setup MetaCoin's Smart Contract

```
npm install

node scripts/1-connect.js
|ChainId: 44787
|Block height: 4226591
|Successfully connected to Celo Network

node scripts/2-create_account.js
|address:  0x....
|privateKey:  0x....

Edit .env for REST_URL, ADDRESS and PRIVATE_KEY
Fund your Testnet Account (https://celo.org/developers/faucet)

node scripts/3-query.js
|CELO balance:  10000000000000000000
|cUSD balance:  20000000000000000000
|Locked CELO balance:  0
|Pending balance:  0

truffle compile
truffle migrate --network alfajores

```

REF: https://learn.figment.io/network-documentation/celo/tutorial/5.smart-contract
