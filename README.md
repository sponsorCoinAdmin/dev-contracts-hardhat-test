# dev-contracts-spCoin

# SETUP
clone this project to a local machine<BR>
Install the node package libries<BR>
npm i

# TESTING
execute <BR>
npx hardhat test
 
# OPTIONAL - MANUAL INSTALL TO SET UP TESTING FROM SCRATCH

VISUAL STUDIO CODE INSTALL PLUGIN<BR>
Nomic Foundation

# INSTALLING HARDHAT
npm install --save-dev hardhat

# REQUIRED SUPPORT PACKAGES 
 npm install --save-dev @nomicfoundation/hardhat-toolbox <BR>
 npm install --save-dev @nomiclabs/hardhat-waffle 'ethereum-waffle@^3.0.0' @nomiclabs/hardhat-ethers 'ethers@^5.0.0'<BR>

Add the following code snippet at the top of your hardhat.config.js file<BR>
require("@nomiclabs/hardhat-waffle");<BR>
<BR>
npm audit fix --force<BR>

# IMPORTANT HARDHAT GLOBAL COMMANDS
npx hardhat help
