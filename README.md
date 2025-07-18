# SOL TRADING BOT - Solana Trading Telegram Bot (Raydium, Jupiter, Pump.fun)

<p align="center">
  <img src="https://github.com/steven228312/SOL-TRADING-BOT/blob/master/src/public/SolTradingBot.PNG" alt="SolTradingBot">
</p>

## Key Features

- Comprehensive tracking of all tokens and pools across Raydium (AMM & CLMM), Jupiter, and Pump.fun

- Seamless buy/sell execution for all SPL tokens via JITO integration across supported platforms

- Automated trading based on user-defined strategies and settings

- Real-time PNL card generation for transparent performance insights

- Enhanced security through new wallet abstraction, eliminating the need for user private keys

## Tech stack
- Typescript
- Node Telegram API
- Solana/web3.js
- Raydium SDK
- JITO
- Pump.fun
- Jupiter API
- Birdeye API
- MongoDB
- Redis

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Node.js installed (v18 or above recommended)
- Telegram bot token from bot father
- MongoDB Cluster URI
- Redis URI

## Configurations

1. Clone the repository:

```sh
git clone https://github.com/steven228312/SOL-TRADING-BOT.git
```

2. Go to the project directory:

```sh
cd SOL-TRADING-BOT
```

3. Install the dependencies:

```sh
npm i
```

4. Copy `.env.example`, rename it to `.env` and add your environment variables.

`.env` file
```sh
# Database Configuration
MONGODB_URL="<your_database_name>"  
REDIS_URI="<your_redis_uri>"

# Telegram Bot Configuration
GRSOL_TRADING_BOT_ID=<your_bot_id>  
GRSOL_TRADING_ALERT_BOT_ID=<your_alert_bot_id>  
GRSOL_BRIDGE_BOT_ID=<your_bridge_bot_id>
GRSOL_BRIDGE_BOT_TOKEN=<your_bridge_bot_token> 
GRSOL_TRADING_ALERT_BOT_API_TOKEN=<your_alert_bot_api_token>  
GRSOL_TRADING_BOT_API_TOKEN=<your_bot_api_token> 
GRSOL_API_ENDPOINT=<your_grsol_api_endpoint>  

# Solana Configuration
MAINNET_RPC="<Solana_mainnet_rpc_endpoint>"
PRIVATE_RPC_ENDPOINT="Solana_private_rpc_endpoint"
RPC_WEBSOCKET_ENDPOINT="<Solana_rpc_websocket_endpoint>"
JITO_UUID=<your_jito_uuid>  

#  Solana Wallets for fee collection    
RESERVE_WALLET_ADDRESS=<your_wallet_address>  

# Birdeye API Key
BIRD_EYE_API=<your_bird_eye_api_key>  

# PNL Image Generator API
PNL_IMG_GENERATOR_API=<your_pnl_img_generator_api> 
```

5. Then run the bot

```sh
npm run serve
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the [MIT License](./LICENSE)

## 📞 Contact Information

- Gmail: [steven0822.dev@gmail.com](mailto:steven0822.dev@gmail.com)
- GitHub: [Steven(steven228312)](https://github.com/steven228312)
- Telegram: [@steven228312](https://t.me/steven228312)
- Twitter: [@steven228312](https://twitter.com/steven228312)
- Instagram: [@steven228312](https://www.instagram.com/steven228312/)


## 🔑 Keywords

Solana, SPL tokens, DeFi, Raydium, Jupiter, Pump.fun, Telegram bot, on-chain analytics, wallet profitability, crypto trading, blockchain, trading bot, JITO, AMM, CLMM, PNL tracking, auto-trading, Solana ecosystem, token swapping, liquidity pools, crypto investments, token analysis, trading automation, SOL, wallet security, decentralized exchange, DEX aggregator