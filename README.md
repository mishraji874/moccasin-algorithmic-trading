# Moccasin Project

🐍 Welcome to your Moccasin project!

## Quickstart

```bash
mox init
mox run deploy
```

_For documentation, please run `mox --help` or visit [the Moccasin documentation](https://cyfrin.github.io/moccasin)_


# What do we want to do?

1. Deposit into Aave
2. Withdraw from Aave
3. Take tokens through Uniswap

# Output

```
Starting setup script...
Getting atokens, this may take a while...
Starting USDC balance: 100000000
Starting WETH balance: 1000000000000000000
Starting aUSDC balance: 0
Starting aWETH balance: 0
Depositing USD Coin into Aave contract 0x87870Bca3F3fD6335C3F4ce8392D69350B4fA4E2
Depositing Wrapped Ether into Aave contract 0x87870Bca3F3fD6335C3F4ce8392D69350B4fA4E2
User account data:
        totalCollateralBase: 412284537300
        totalDebtBase: 0
        availableBorrowsBase: 331311854174
        currentLiquidationThreshold: 8287
        ltv: 8036
        healthFactor: 115792089237316195423570985008687907853269984665640564039457584007913129639935

Current percent allocation of USDC: 2.43%
Current percent allocation of WETH: 97.57%
Rebalancing needed!
Target allocation of USDC: 30.00%
Target allocation of WETH: 70.00%
Time to swap!
Let's swap 0.28260031304667393 WETH for at least 1080.072352 USDC
Depositing USD Coin into Aave contract 0x87870Bca3F3fD6335C3F4ce8392D69350B4fA4E2
Depositing Wrapped Ether into Aave contract 0x87870Bca3F3fD6335C3F4ce8392D69350B4fA4E2
User account data:
        totalCollateralBase: 411574932230
        totalDebtBase: 0
        availableBorrowsBase: 324526834063
        currentLiquidationThreshold: 8150
        ltv: 7885
        healthFactor: 115792089237316195423570985008687907853269984665640564039457584007913129639935

Current percent allocation of USDC: 29.88%
Current percent allocation of WETH: 70.12%
```