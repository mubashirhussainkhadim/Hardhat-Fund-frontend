html-fund-me-fcc
HTML / Javascript Fund Me (Full Stack / Front End)

This is a minimalistic example what you can find in the metamask docs.
Requirements

    git
        You'll know you've installed it right if you can run:
            git --version
    Metamask
        This is a browser extension that lets you interact with the blockchain.
    Nodejs
        You'll know you've installed nodejs right if you can run:
            node --version And get an ouput like: vx.x.x
    Yarn instead of npm
        You'll know you've installed yarn right if you can run:
            yarn --version And get an output like: x.x.x
            You might need to install it with npm

Confused? You can run git checkout nodejs-edition if you'd like to see this with nodejs.
Typescript

For this demo project, we do not have a typescript edition. Please see the NextJS projects for a professional typescript front end.
Optional Gitpod

If you can't or don't want to run and install locally, you can work with this repo in Gitpod. If you do this, you can skip the clone this repo part.

Open in Gitpod
Quickstart

    Clone the repo

git clone https://github.com/PatrickAlphaC/html-fund-me-fcc
cd html-fund-me-fcc

    Run the file.

You can usually just double click the file to "run it in the browser". Or you can right click the file in your VSCode and run "open with live server".

Optionally:

If you'd like to run with prettier formatting, or don't have a way to run your file in the browser, run:

yarn
yarn http-server

And you should see a small button that says "connect".

Connect

Hit it, and you should see metamask pop up.
Execute a transaction

If you want to execute a transaction follow this:

Make sure you have the following installed:

    You'll need to open up a second terminal and run:

git clone https://github.com/PatrickAlphaC/hardhat-fund-me-fcc
cd hardhat-fund-me-fcc
yarn
yarn hardhat node

This will deploy a sample contract and start a local hardhat blockchain.

    Update your constants.js with the new contract address.

In your constants.js file, update the variable contractAddress with the address of the deployed "FundMe" contract. You'll see it near the top of the hardhat output.

    Connect your metamask to your local hardhat blockchain.

    PLEASE USE A METAMASK ACCOUNT THAT ISNT ASSOCIATED WITH ANY REAL MONEY. I usually use a few different browser profiles to separate my metamasks easily.

In the output of the above command, take one of the private key accounts and import it into your metamask.

Additionally, add your localhost with chainid 31337 to your metamask.

    Reserve the front end with yarn http-server, input an amount in the text box, and hit fund button after connecting

Thank you!

