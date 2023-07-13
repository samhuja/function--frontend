# Simple Contract with Frontend

This repository contains a simple Solidity contract with 2-3 functions, along with an HTML/JavaScript frontend to display the values of those functions.

## Contract

The Solidity contract (`SimpleContract.sol`) includes the following functions:

- `setData`: Sets a new value for a state variable called `data`.
- `getData`: Retrieves the current value of `data`.
- (Optional) `multiplyData`: Multiplies the existing value of `data` by a provided multiplier.

## Frontend

The HTML/JavaScript frontend (`index.html`) allows users to interact with the contract and display the values of its functions. It includes the following features:

- Input field and button to set a new value for `data`.
- Button to retrieve the current value of `data` and display it on the page.
- (Optional) Input field and button to multiply the existing value of `data` by a provided multiplier.

## Getting Started

To run the frontend and interact with the contract, follow these steps:

1. Ensure you have a compatible Ethereum provider (e.g., MetaMask) installed and set up in your browser.
2. Deploy the Solidity contract to an Ethereum network of your choice and note the contract address.
3. Update the `contractAddress` and `contractABI` variables in the JavaScript code of `index.html` with your deployed contract's values.
4. Open `index.html` in a browser.

## Dependencies

The project has the following dependencies:

- [web3.js](https://github.com/ethereum/web3.js) (v1.3.0 or later)
- (Optional) [ethers.js](https://github.com/ethers-io/ethers.js/) (v5.0.0 or later)

You can install these dependencies using npm:

```shell
npm install web3@1.3.0
npm install ethers@5.0.0
