# base1f
Measuring Gas Savings on Base Compared to Ethereum  Base is dramatically cheaper than Ethereum.  Python:
eth_gas = Web3(Web3.HTTPProvider("https://ethereum.publicnode.com")).eth.gas_price
base_gas = w3.eth.gas_price

print("ETH / Base fee ratio:", eth_gas / base_gas)
