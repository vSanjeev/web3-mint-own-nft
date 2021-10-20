# Blockchain Project - Mint own NFT - Ethereum (Rinkeby)

A simple smart contract to mint NFTS on ETH rinkeby test network.

The run scripts deployes the smart contract locally, whereas the deploy script deployed to smart contract to a network of choice.

```shell
npm ci

npx hardhat run scripts/run.js
npx hardhat run scripts/deploy.js --network rinkeby
```

npm ci - installs all the package dependencies. Post this, you'd have to register at alchemy.com to get a rinkeby API key.

Once, you get the API keys, create a ```.env``` file inside the backend folder with the following 2 lines in it. The private key is your private key of your wallet.

```shell
RINKEBY_STAGING_ALCHEMY_KEY = 
PRIVATE_KEY = 
```

Before uploading your code anywhere, make sure it doesn't have your private key in it. Happy venturing!