# Binance Futures Testnet Trading Bot

## Setup

1. Install dependencies:
   pip install -r requirements.txt

2. Create .env file:
   API_KEY=your_key
   API_SECRET=your_secret

## Run

### MARKET Order
python -m bot.cli --symbol BTCUSDT --side BUY --type MARKET --quantity 0.001

### LIMIT Order
python -m bot.cli --symbol BTCUSDT --side SELL --type LIMIT --quantity 0.001 --price 30000

## Features
- MARKET + LIMIT orders
- BUY & SELL support
- CLI input validation
- Logging to file
- Error handling
