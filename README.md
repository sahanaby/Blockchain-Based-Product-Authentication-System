# 🔐 Blockchain-Based Product Authentication System

## 📌 Overview
This project is a Blockchain-based Product Authentication System designed to prevent counterfeit products using decentralized ledger technology. It enables secure product registration and tamper-proof verification through smart contracts.

## 🚀 Features
- Smart contract-based product registration
- Unique product ID generation
- Tamper-proof blockchain storage
- Real-time product authenticity verification
- Transparent and decentralized system

## 🛠 Tech Stack
- Solidity (Smart Contracts)
- Ethereum / Ganache
- Web3.js / Ethers.js
- Flask / Node.js
- HTML / CSS / React
- MetaMask

## ⚙️ How to Run
1️⃣ Deploy Smart Contract

Install and open Ganache.

Create a new workspace and select the Truffle project.

Start Ganache to generate local blockchain accounts.

2️⃣ Configure MetaMask

Open MetaMask extension.

Add a new network (Ganache RPC URL).

Copy a private key from Ganache.

In MetaMask → Import Account → Paste the private key.

Repeat if multiple accounts are required.

3️⃣ Compile and Deploy Smart Contracts

Open terminal inside the project folder and run:

npm install
truffle compile
truffle migrate


This will compile and deploy the smart contracts to the Ganache blockchain.

4️⃣ Start Backend Server

Ensure Web3 is configured properly in the backend.

npm start


(or run the appropriate backend command if using Flask/Node.js)

5️⃣ Run Frontend Application
npm run dev


The application will launch in the browser and automatically connect to MetaMask.

6️⃣ Verify Product

Enter or scan the Product ID.

The system retrieves blockchain data.

Displays authenticity status of the product.

## 🎯 Objective
To build a secure, transparent, and decentralized system to eliminate counterfeit risks in supply chains.
