
# Hardhat-Simple-Storage

-https://www.youtube.com/watch?v=gyMwXuJrbJQ&ab_channel=freeCodeCamp.org
-https://www.youtube.com/watch?v=gyMwXuJrbJQ&t=30017s


## Code:
- https://github.com/smartcontractkit/full-blockchain-solidity-course-js
- Has all the Lessons Code with Bookmark Links of Videos 
- https://github.com/PatrickAlphaC/hardhat-simple-storage-fcc
- Code for this 
- Harhat Documentation
- https://hardhat.org/tutorial

## Done
- Added prettier package to remove Semicolons in the code
- Hardhat comes with default Hardhat Network 
- So, it gets deployed to local internal network when deployed 
- Deploy
- npx hardhat run scripts/deploy.js --network hardhat

## Hardhat Goerli 
- https://www.youtube.com/watch?v=ZoHY_ujIeXo&list=PLgPmWS2dQHW9mucRpDVe16j9Qn74ZXqcD&index=9&ab_channel=CodeEater

- Check this on how to get the Private Key
- Also on the Transaction view in Etherscan

## Verify

- npx hardhat verify --network mainnet DEPLOYED_CONTRACT_ADDRESS "Constructor argument 1"

## Troubleshooting

- Delete artifacts and cache .Rerun yarn run

## Tasks
- yarn hardhat block-number --network goerli
- Scripts are better than Tasks for local development

## Local Node
- yarn hardhat node
- To spin up the node in local similar to Ganache

## Console Interaction with Node
- yarn hardhat console --network localhost
- Opens up the console to execute anything from shell instead of the deploy scripts 

## Hardhat Gas Reporter
- To test how much gas each function in the contract needs
- Create an account in CoinMarketCap to get the API Key
- https://pro.coinmarketcap.com/account

## Test Coverage 
- yarn hardhat coverage 