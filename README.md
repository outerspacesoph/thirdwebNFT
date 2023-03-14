# Hardhat Smart Contract deployed w/ Thirdweb

This project demonstrates a basic Hardhat smart contract. It comes with a sample contract, a test for that contract, and a script that deploys that contract. However, with Thirdweb, no scripts are needed.

To set up a simple Hardhat project follow these steps:

In the project terminal execute these commands

1. npm init --yes
2. npm install --save-dev hardhat @nomicfoundation/hardhat-toolbox
3. npx hardhat
4. Select Create a Javascript Project
5. npm install @openzeppelin/contracts
6. Keep the sample smart contract or create your own
7. npx hardhat compile
8. npx thirdweb deploy
