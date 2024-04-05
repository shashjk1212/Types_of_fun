# JersyToken

JersyToken is a simple ERC20 token smart contract developed on the Ethereum blockchain. This contract allows for the creation, transfer, and burning of tokens. Below are the key features and functionalities of the contract:

## Features:

1. **ERC20 Compatibility**: JersyToken adheres to the ERC20 standard, making it compatible with existing Ethereum ecosystem tools and platforms.

2. **Minting**: The contract owner has the ability to mint new tokens. This feature allows for the controlled creation of tokens.

3. **Burning**: Token holders can burn their tokens, removing them permanently from circulation. This feature can be used for various purposes, such as token destruction or reducing token supply.

4. **Transfer**: The contract overrides the transfer function from the ERC20 standard to include additional checks, ensuring that transferred quantities are valid and that the sender has a sufficient balance.

5. **Ownership**: The contract inherits from the Ownable contract provided by the OpenZeppelin library, allowing for ownership management. The owner has exclusive access to certain functions like minting tokens.

## Usage:

- **Deployment**: Deploy the contract to the Ethereum blockchain.
- **Minting**: Only the owner can mint new tokens. Use the `mint` function to create new tokens and assign them to a specific address.
- **Transferring**: Users can transfer tokens to other addresses using the `transfer` function. Additional checks are performed to ensure validity.
- **Burning**: Token holders can burn their tokens using the `burn` function, permanently removing them from circulation.


## Development Environment:

- This contract is developed using Solidity version 0.8.0.
- It imports ERC20 and Ownable contracts from the OpenZeppelin library.

## License:

This contract is released under the MIT License.

## Author

shashank j k

shashjk5@gmail.com
