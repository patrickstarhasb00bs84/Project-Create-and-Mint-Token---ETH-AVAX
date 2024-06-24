# ETH + AVAX Intermediate: Create and Mint Token Project

This project demonstrates the creation and deployment of a custom ERC20 token contract named RVC (RevCoin) using Solidity.
## Description

This project demonstrates the creation of a custom ERC20 token contract named RVC (RevCoin) using Solidity. The contract allows for controlled minting of tokens by the contract owner, transfers between users, and burning of tokens by token holders. It is built upon the OpenZeppelin ERC20 standard, ensuring reliability and adherence to best practices in token development on Ethereum and Avalanche (AVAX) blockchains.

## Executing program

To deploy and interact with the RVC token contract, follow these steps using the Remix online compiler:

1. **Set Solidity Compiler Version:**
   - Open Remix (https://remix.ethereum.org/).
   - Ensure the Solidity compiler version is set to 0.8.0 or higher.

2. **Import OpenZeppelin Contracts:**
   - In the Remix sidebar, create a new file named `RVC.sol`.
   - Copy and paste the entire code from `RVC.sol` provided in this repository.

3. **Compile the Contract:**
   - Click on the 'Solidity Compiler' tab in Remix.
   - Compile the `RVC.sol` contract. Ensure there are no errors.

4. **Deploy the Contract:**
   - Switch to the 'Deploy & Run Transactions' tab in Remix.
   - Select `RVC` from the contract dropdown (it should automatically detect your contract).
   - Enter the initial supply parameter and click on 'Deploy'.

5. **Interact with the Contract:**
   - Once deployed, you can interact with the contract using the available functions (`mint`, `burn`, `transferRev`).
   - Connect your Ethereum wallet to Remix to execute transactions.

## Authors

Metacrafter Chris  
[@metacraftersio](https://twitter.com/metacraftersio)

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.
