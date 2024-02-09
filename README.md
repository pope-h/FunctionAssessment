# Function Assessment

This Solidity program is a simple program that has at least two functions. Value of the functions from the smart contract are visible on the frontend of the application that demonstrates the basic syntax and functionality of the Solidity programming language.

## Description

This program is a simple contract written in Solidity, a programming language used for developing smart contracts on the Ethereum blockchain. The contract has four functions that tests the withdraw, deposit, and transfer functionalitries. A frontend design is added for ease of use.
## Getting Started

### Executing program

After cloning the github, you will want to do the following to get the code running on your computer.

Inside the project directory, in the terminal type: npm i
Open two additional terminals in your VS code
In the second terminal type: npx hardhat node
In the third terminal, type: npx hardhat run --network localhost scripts/deploy.js
(I would personally suggest to run the command `npx node deploy` and replace the new contract address gotten with the one in the index.js file before running the above)
Back in the first terminal, type npm run dev to launch the front-end.
After this, the project will be running on your localhost. Typically at http://localhost:3000/


## Authors

Ekarika Nsemeke


## License

This project is licensed under the MIT License - see the LICENSE.md file for details