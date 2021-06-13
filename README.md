# hlf2-network
A Hyperledger Fabric network with a ERC20 Token java chaincode

More info in Medium tutorials
* [Create java chaincode](https://medium.com/coinmonks/how-to-create-a-java-chaincode-and-deploy-in-a-hyperledger-fabric-2-network-65199e5f645d) 

# Installation instructions

1. Download the template:
`git clone https://github.com/ialberquilla/hlf1.4-couchdb`

2. Download bin and config files
`curl -sSL https://bit.ly/2ysbOFE | bash -s -- -d -s`


# Start the network
`./network.sh up createChannel`

# Deploy the chaincode
`./network.sh deployCC -l java` :

This script also test the ERc20 function like transfer. You can add more functionality.You can check the source code.


# Stop the network
`./network.sh down`

