# Foundry Simple Storage

This is an example solidity smart contract project that makes a simple storage contract.

## Commands

```sh
# Initialize foundry project
forge init

# To run local development network
anvil

# To add private key to deployment account and then simulate deployment of contract
forge create <CONTRACT-NAME>.sol --interactive

# To simulate deployment of a script
forge script script/<CONTRACT-NAME>.s.sol

# To deploy a script to a running network
forge script script/<CONTRACT-NAME>.s.sol --rpc-url <RPC-URL>

# To deploy a script to a running network and broadcast it
forge script script/<CONTRACT-NAME>.s.sol --rpc-url <RPC-URL> --broadcast --private-key <PRIVATE-KEY>

# To convert from hex value to decimal number
cast --to-base <HEX> dec

# To send a transaction
cast send <CONTRACT-ADDRESS> "<FUNCTION-NAME>(<INPUT-TYPE, INPUT-TYPE, ...>)" <INPUT-VALUE INPUT-VALUE ...> --rpc-url <RPC-URL> --private-key <PRIVATE-KEY>

# To call a gasless function
cast call <CONTRACT-ADDRESS> "<FUNCTION-NAME>(<INPUT-TYPE, INPUT-TYPE, ...>)" <INPUT-VALUE INPUT-VALUE ...> --rpc-url <RPC-URL> --private-key <PRIVATE-KEY>

# To format solidity code
forge fmt
```
