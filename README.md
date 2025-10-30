# Kardia Kingdom NFT Marketplace

![KardiaChain](https://img.shields.io/badge/Network-KardiaChain-green)
![Next.js](https://img.shields.io/badge/Next.js-13.0.0-black)
![TypeScript](https://img.shields.io/badge/TypeScript-4.8.4-blue)
![Web3](https://img.shields.io/badge/Web3-1.7.4-orange)

A decentralized NFT marketplace built on the KardiaChain network, featuring the **Kai Kongs** collection - the first ever algorithmically generated 10K PFP collection on KardiaChain.

## 🌟 About Kardia Kingdom

Kardia Kingdom is an Endless Realm Built on the KardiaChain Network with a mission to create a better world by giving back to people who need it the most. As an entirely Non-Profit entity, all profits are reinvested into the project for holders/community or distributed through airdrops, events, and giveaways.

### Mission
- Build the first NFT community on the KardiaChain network
- Empower creators and artists to deploy NFT art and collections
- Foster community growth through legacy rewards and airdrops
- Provide an accessible marketplace for NFT trading

## 🎨 Features

- **NFT Minting**: Mint Kai Kongs directly from the website (15 KAI per Kong, max 3 per transaction)
- **Marketplace**: Browse and purchase listed NFTs with real-time pricing
- **Collection Analytics**: View floor price, total volume, and collection statistics
- **Wallet Integration**: Seamless MetaMask integration for KardiaChain
- **Responsive Design**: Beautiful UI built with Tailwind CSS
- **NFT Details**: Individual NFT pages with metadata and traits
- **Pagination**: Browse large collections efficiently

## 🛠️ Tech Stack

- **Frontend**: Next.js 13, React 18, TypeScript
- **Blockchain**: Web3.js, KardiaChain Network
- **Styling**: Tailwind CSS
- **Smart Contracts**: Solidity ^0.8.4 (ERC721)
- **Storage**: IPFS (Pinata)

## 📦 Smart Contracts

### NFT Contract (Kai Kongs)
- **Address**: `0xf6FFA2a5685c2Ad53eEDa1197f54FFc1b22f5c1c`
- **Standard**: ERC721 Enumerable
- **Max Supply**: 10,000 NFTs
- **Mint Price**: 15 KAI

### Marketplace Contract
- **Address**: `0x3D86B80898b223C0F26166670AA8638af263cBA2`
- **Features**: Buy/Sell NFTs, Floor price tracking, Volume metrics

## 🚀 Getting Started

### Prerequisites

- Node.js 18+ installed
- MetaMask wallet configured for KardiaChain
- Basic knowledge of Web3 and blockchain

### Installation

1. Clone the repository:
```bash
git clone https://github.com/superdev947/KD-NFT-Marketplace.git
cd KD-NFT-Marketplace
```

2. Install dependencies:
```bash
npm install
```

3. Run the development server:
```bash
npm run dev
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser

### Build for Production

```bash
npm run build
npm start
```

## 🌐 KardiaChain Network Configuration

Add KardiaChain to MetaMask:

- **Network Name**: KardiaChain Mainnet
- **RPC URL**: https://dev.kardiachain.io/
- **Chain ID**: 24 (0x18)
- **Currency Symbol**: KAI
- **Block Explorer**: https://explorer.kardiachain.io/

## 📁 Project Structure

```
KD-NFT-Marketplace/
├── components/
│   ├── Mint.tsx              # Minting component
│   └── Pagination.tsx        # Pagination component
├── pages/
│   ├── index.tsx             # Home page
│   ├── kongs.tsx             # Kai Kongs collection page
│   ├── market.tsx            # Marketplace page
│   └── nft/[id]/index.tsx    # Individual NFT detail page
├── public/
│   └── _metadata_with_rarity.json
├── styles/
│   └── globals.css
├── utls/
│   └── paginate.tsx          # Pagination utility
├── contract.sol              # NFT smart contract
├── contract-abi.json         # NFT contract ABI
└── marketplace-contract-abi.json
```

## 🎯 Key Features Explained

### Minting
- Users can mint 1-3 Kai Kongs per transaction
- Automatic network switching to KardiaChain
- Real-time supply tracking
- Price: 15 KAI per Kong

### Marketplace
- List and buy NFTs
- Real-time floor price calculation
- Volume tracking across all trades
- Detailed NFT metadata display

### Collections
- View all available collections
- Collection-specific analytics
- IPFS-hosted metadata and images

## 🔧 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm start` - Start production server
- `npm run lint` - Run ESLint

## 🤝 Contributing

Contributions are welcome! This is a community-driven project aimed at growing the KardiaChain ecosystem.
