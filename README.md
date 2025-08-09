# Launch Meme Coin

## Technology Stack & Tools

- Solidity (Writing Smart Contracts & Tests)
- Javascript
- [Hardhat](https://hardhat.org/) (Development Framework)
- [Ethers.js](https://docs.ethers.io/v5/) (Blockchain Interaction)
- [Next.js](https://nextjs.org/) (Frontend Framework)

## Setting Up

### 1. Clone/Download the Repository

### 2. Install Dependencies:

```
npm install
```

### 3. Run tests

```
npx hardhat test
```

### 4. Start Hardhat node

```
npx hardhat node
```

### 5. Run deployment script

In a new terminal run the following:

```
npx hardhat ignition deploy ignition/modules/Factory.js --network localhost
```

If want to append the deployed contract add `--reset` at the end:

```
npx hardhat ignition deploy ignition/modules/Factory.js --network localhost --reset
```

### 6. Start frontend

```
npm run dev

```
### visual diagram
<img width="1303" height="647" alt="Screenshot 2025-08-09 at 13 56 41" src="https://github.com/user-attachments/assets/c9708d42-c626-40a7-a34b-572c73330b41" />


