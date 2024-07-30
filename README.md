# Swisstronik Tesnet Techinal Task 5 Deploy Private NFT


### 1. Clone Repository

```bash
git clone https://github.com/rpxtxt/swisstronik-deploy-private-nft.git
```
```bash
cd swisstronik-deploy-private-nft
```

### 2. Install Dependency

```bash
npm install
```

### 3. Set .env File

create .env file in root project

```bash
touch .env
```

add this to your .env file
```bash
PRIVATE_KEY="your private key"
```

### 4. Update Smart Contract (Skipp if you won't modify NFT name)

- Open contracts folder
- Open PrivateNft.sol

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