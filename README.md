## Create and Mint Token

The solidity program "Create and Mint Token" will demonstrate the use of ERC20 Contract.

## Description

This smart contract, written in Solidity, defines an ERC20 token named "Chakshit" with the symbol "CT". The contract uses OpenZeppelin's ERC20 implementation to leverage standardized functionalities and inherits from the ERC20 base contract.

Upon deployment, the contract assigns the deployer as the owner. This owner designation is critical because the contract includes an onlyOwner modifier, restricting certain actions to only the owner. Specifically, the mint function, which allows the creation of new tokens, can only be called by the owner. This ensures controlled token minting, preventing arbitrary token creation by other users.

The contract also defines a burn function, allowing any token holder to destroy (or burn) a specified amount of their tokens, reducing the total supply. This function is accessible to any user who owns tokens, enabling decentralized control over token burning.

Moreover, the contract overrides the transfer function from the ERC20 base contract to allow token transfers between addresses. This function facilitates the transfer of tokens from the sender's account to a specified recipient, ensuring standard ERC20 token transfer functionality.

Overall, this contract defines a basic ERC20 token with controlled minting, user-enabled burning, and standard transfer capabilities, providing a foundation for a versatile cryptocurrency.

### Installing

To download the code, you can visit the following file path:- https://github.com/chakshit2004h/ETH_Intermidate_Module3/blob/main/MintToken.sol

### Executing program

To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at https://remix.ethereum.org/.

Once you are on the Remix website, create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension (e.g., HelloWorld.sol). Copy and paste the following code into the file.

To compile the code, click on the "Solidity Compiler" tab in the left-hand sidebar. Make sure the "Compiler" option is set to "0.8.25" (or another compatible version), and then click on the "Compile MintToken.sol" button.

Once the code is compiled, you can deploy the contract by clicking on the "Deploy & Run Transactions" tab in the left-hand sidebar. Select the "MintToken" contract from the dropdown menu, and then click on the "Deploy" button.

Once the contract is deployed, you will use the various ERC20 Contracts in build functions.


## Authors


Metacrafter Chris
@metacraftersio


## License

This project is licensed under the MIT License - see the LICENSE.md file for details
