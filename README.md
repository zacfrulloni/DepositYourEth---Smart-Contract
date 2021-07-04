# DepositYourEth---Smart-Contract
DepositYourEth is a smart contract that can be used to transact ether between metamask accounts. It is run on the rinkeby test network by using a infura api, no real ether is transacted.
For this case I have used deposits sent from tenants to a landlord. The ether can only be withdrawn from the landlord address.
Steps to Reproduce:

-install dependencies;
- insert rinekby infura api + 12 word mnemonic;
- run: node compile and node deploy ;
- copy deployed address to deposits.js;
- to run on localhost: npm run dev;
