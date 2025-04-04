# NFT Sample Hardhat Project

This project demonstrates a basic NFT Marketplace smart contract use case:

## CLI

Try running some of the following tasks:

```shell
npx hardhat help
npx hardhat test
REPORT_GAS=true npx hardhat test
```

### Run local node

```shell
npx hardhat node
```

### Deploy NFT smart contract

```shell
npx hardhat ignition deploy ./ignition/modules/NFTMarketplace.ts --network localhost
```

Wait for successful deployment:

```plaintext
Deployed Addresses

NFTMarketplace#NFTMarketplace - 0x5FbDB2315678afecb367f032d93F642f64180aa3
```

Done! Now, you can use the above `0x***` smart-contract address to interact with the deployed NFT Marketplace. This address can be used in the following ways:

1. **Web3 Integration**: Use the contract address in your frontend application to interact with the NFT Marketplace using libraries like `ethers.js` or `web3.js`.
2. **Smart Contract Interaction**: Reference this address in other smart contracts to call functions or interact with the deployed NFT Marketplace.
3. **Testing**: Use the address in your test scripts to verify the functionality of the deployed contract.

Make sure to update your environment variables or configuration files with the deployed contract address to properly integrate.
