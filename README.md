# Mod-4-DegenToken

Degen Gaming ERC20 Token is a custom token created for the Degen Gaming platform. This token is used as a reward system for players and can be redeemed for in-game items in the Degen Gaming store.

## Introduction

Degen Gaming ERC20 Token is a standard ERC20 token deployed on the Avalanche network. It allows the Degen Gaming platform to create new tokens and distribute them to players as rewards. Players can transfer tokens to each other, check their token balance, and redeem tokens for in-game items in the Degen Gaming store.

## Features

- Minting new tokens: Only the owner of the contract can mint new tokens and distribute them as rewards to players.
- Transferring tokens: Players can transfer their tokens to other players or accounts.
- Redeeming tokens: Players can use their tokens to purchase in-game items from the Degen Gaming store.
- Checking token balance: Players can check their token balance at any time to see how many tokens they have.
- Burning tokens: Players can burn (destroy) their own tokens if they no longer need them.

## Deployment on Avalanche Network

The Degen Gaming ERC20 Token smart contract has been deployed on the Avalanche network. Players can interact with the token using any compatible Ethereum wallet or blockchain explorer.

## Prerequisites
- Install a compatible web3-enabled browser or browser extension like Metamask.
- Create a wallet and get some test AVAX (Avalanche tokens) for interacting with the contract on the Avalanche C-Chain testnet.
- Deploying the Contract on Remix IDE
- Open Remix IDE: Go to https://remix.ethereum.org/ to access the Remix IDE in your web browser.

- Create a New File: Click on the "+" icon on the left panel and create a new file named degenToken.sol.

- Copy the Code: Copy and paste the code of the degenToken.sol smart contract into the Remix IDE editor.

- Compile the Contract: In the Remix IDE, go to the "Solidity Compiler" tab on the right panel. Select the appropriate compiler version (e.g., 0.8.0) and click "Compile 
  degenToken.sol".

- Deploy the Contract: After successful compilation, go to the "Deploy & Run Transactions" tab on the right panel. Select "Injected Web3" as the environment (to use 
  Metamask), and ensure you are connected to the Avalanche testnet.

- Deploy the Contract: Click on the "Deploy" button to deploy the DegenToken contract to the Avalanche testnet. Metamask will prompt you to confirm the transaction. 
  Confirm the transaction with the required gas fee.

- Interact with the Contract: Once the contract is deployed, you will see the contract address on the Remix IDE interface. You can copy the contract address and paste it 
  into the DegenToken ABI field to interact with the contract.

## Interacting with the Contract
- **Mint New Tokens** : To mint new tokens, call the mint function by providing the recipient's address and the amount of tokens to mint. Ensure that the Metamask account 
 is the contract owner to perform this operation.

- **Transfer Tokens** : To transfer tokens to another account, call the transfer function with the recipient's address and the amount of tokens to transfer.

- **Redeem Tokens** : Implement the logic for redeeming tokens in your Degen Gaming platform. Call the redeem function with the appropriate parameters to redeem tokens for 
  in-game items.

- **Check Token Balance** : To check the balance of a specific address, call the balanceOf function and provide the address as a parameter.

- **Burn Tokens** : To burn (destroy) tokens that you own, call the burn function and specify the amount of tokens to burn.



## Usage

To interact with the Degen Gaming ERC20 Token, players can use any Ethereum wallet that supports Avalanche or a compatible blockchain explorer.

The token contract provides the following functions:

- `transfer`: To transfer tokens to another address.
- `approve`: To approve a third-party address to spend tokens on your behalf.
- `transferFrom`: To allow a third-party address to transfer tokens on your behalf.
- `balanceOf`: To check the token balance of a specific address.
- `allowance`: To check the amount of tokens approved for spending by a third-party address.
- `mint`: Only the contract owner can mint new tokens and distribute them as rewards.
- `redeem`: Players can use this function to redeem their tokens for in-game items from the Degen Gaming store.
- `burn`: Players can burn their own tokens if they no longer need them.

## Author

**SAURYA PRATAP**

- GitHub: https://github.com/saurya25122001
- Email:  22bcs80056@cuchd.in

## License

This project is released under the [MIT License](https://github.com/saurya25122001/Mod-4-DegenToken/blob/cb864a6b38174b863702c37981e5aeb573361f04/LICENSE)
