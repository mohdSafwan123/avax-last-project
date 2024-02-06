# Simple Solidity Smart Contract and Web3 Frontend

This project consists of a simple Solidity smart contract and a corresponding web3 frontend for interacting with the Ethereum blockchain. The smart contract, written in Solidity, allows users to set and retrieve a string variable. The frontend, built using HTML, CSS, and JavaScript with the ethers.js library, facilitates connecting to a wallet (MetaMask) and interacting with the smart contract.
Smart Contract (Solidity)

    Contract Name: variable
    Functions:
        setName(string memory _myVariable): Sets the value of the contract's string variable.
        getName() public view returns (string memory): Retrieves the current value of the string variable.

Web3 Frontend
Features:

    Connect Wallet:
        MetaMask integration to connect to the user's wallet.
        Displays the connected account address.

    Write Name:
        Allows users to input a name in a text field and write it to the blockchain using the setName function.
        Sends a transaction to set the name, with real-time feedback on the mining process.

    Read Name:
        Retrieves the stored name from the blockchain using the getName function.
        Displays the retrieved name on the frontend.

Instructions:

    Open the HTML file in a web browser.
    Click "Connect Wallet" to connect MetaMask.
    Use the "Write Name" section to input and set a name on the blockchain.
    Click "Read Name" to fetch and display the stored name.

How to Run:

    Ensure MetaMask is installed.
    Deploy the Solidity smart contract to an Ethereum network.
    Update the contractAddress and abi in constants.js with the deployed contract details.
    Open the HTML file in a browser.

Additional Notes:

    The frontend uses ethers.js for interacting with the Ethereum blockchain.
    Real-time feedback on transaction confirmation is provided during the mining process.
