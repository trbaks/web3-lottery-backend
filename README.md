# This is backend for Lottery project; key features of the project:
- Deploys a contract on Ethereum (Rinkeby- Test Network)
- Test cases around contract.
- Features of contract a) Enter contract with minimum amount b) Pick Winner- Restricted to Contract Manager.
- Uses Metamask integrated in your browser for 'gas price' to deploy the contract.


# To run 'npm install'
# Replace following environment variables in .env file with your values:
- METAMASK_WALLET_MNEMONIC=YOUR_METAMASK_MNEUMONIC
- RINKEBY_API_ENDPOINT=Rinkeby Deployment URL.

# To deploy the contract from home directory run "node deploy.js"
# To test the contract run "npm test" 
