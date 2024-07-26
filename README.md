# Swisstronik Tesnet Techinal Task 4 (Mint a PERC20 Token)

  - **[WEBSITE TEST](https://www.swisstronik.com/testnet2/dashboard)** 

## SETUP

### 1. Fork Repository

1. **On the Right-Side Corner you can see `Fork` and Forked this Repository into your Github**.
![image](https://github.com/user-attachments/assets/efaa9471-9ea6-46e9-9eda-2e837792b082)

2. **After Forked, Open Codespaces and direct into Terminal**.
![image](https://github.com/user-attachments/assets/e2139d32-ab86-4b16-be49-c6f85b0f91d5)
![image](https://github.com/user-attachments/assets/72508f17-cbf5-43e8-b2cb-60334c87542a)

3. **Then follow the guides below.**

### 2. Install Dependencies

```bash
npm install
```

### 3. Set .env File

create `.env` file in root project

```bash
PRIVATE_KEY="your private key"
```

### 4. Update Smart Contract (Skip if you won't modify Token Name)

- Open contracts folder
- Open PERC20Sample.sol file
- Feel free to modify token name and token symbol

### 5. Compile Smart Contract

```bash
npm run compile
```

### 6. Deploy Smart Contract

```bash
npm run deploy
```

### 7. Mint Token

```bash
npm run mint
```

### 8. Transfer Token

```bash
npm run transfer
```

### 8. Finsihed

- Open the `deployed-address.ts` (location in utils folder)
- Copy the address and paste the address into [Testnet Dashboard](https://www.swisstronik.com/testnet2/dashboard)
- Open the `tx-hash.txt` (location in utils folder)
- Copy the address and paste the tx hash link into Testnet Dashboard
- push this project to your github and paste your repository link in testnet dashboard
