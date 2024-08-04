```markdown
# StockToken Contract

## Overview
The `StockToken` contract is a Solidity-based ERC20 token that allows users to manage and redeem stocks on the blockchain. It incorporates standard ERC20 functionality along with additional features for stock management.

## Features
- **Mint Tokens:** The contract owner can mint new tokens.
- **Burn Tokens:** Users can burn their tokens to redeem stocks.
- **Transfer Tokens:** Users can transfer tokens to other addresses.
- **Set Stock Prices and Quantities:** The owner can set the prices and quantities of stocks.
- **Redeem Stocks:** Users can redeem stocks by burning tokens based on stock prices.
- **Show Portfolio:** Users can view the list of stocks they own.

## Usage
1. **Deploying the Contract:**
   Use Hardhat or Truffle to deploy the contract to your preferred Ethereum network.

2. **Mint Tokens:**
   The contract owner can mint tokens using the `mintTokens` function.

3. **Set Stock Prices and Quantities:**
   The owner can set the price and quantity of stocks using the `setStockPricesAndQuantities` function.

4. **Redeem Stocks:**
   Users can redeem stocks by calling the `redeemStock` function and specifying the stock name and quantity.

5. **View Portfolio:**
   Users can call the `showPortfolio` function to view their stock holdings.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

