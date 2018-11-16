# Streamr - IATA Hackathon

In this documentation we will outline the steps and tools needed to replicate the Cold Chain Monitoring demo we demostrated during the live webinar. In addition we will provide links to learn more about Streamr platform and how to use its API.

## Streamr Cold Chain Monitoring Demo

Before starting, below are few important links:

* https://metamask.io/  Metamask Chrome plug-in to easily manage your Ethereum accounts
* https://remix.ethereum.org/ Solidity IDE, this is where you can write, deploy and inspect smart contracts 
* https://faucet.rinkeby.io/ Testnet Ether faucet (get free Testnet Ether needed to deploy smart contract and call functions)
* https://rinkeby.etherscan.io/  Testnet blockchain explorer, where you can inspect deployed contracts

First stage, tools setup:
1. Setup Metamask and get ETH
	* Install Metamask plugin on Chrome
	* Create a Metamask account (remember to save your recovery seed words!)
	* Switch to Rinkeby Network from the Main Network
	* Copy your Ethereum address and head to [Rinkeby Faucet](https://faucet.rinkeby.io/) to follow the instructions to get free ETH coins
1. Deploy Cold Chain Monitoring smart contract
	* You can get sample codes from this [repository](https://github.com/streamr-dev/coldchain-demo/tree/master/contracts). You will see the simple version and a more complex one. During the webinar we will be using the simple version.
	* Head to [Remix IDE](https://remix.ethereum.org/) to deploy your smart contract. Here is a [quick tutorial](https://remix.readthedocs.io/en/latest/run_tab.html) on how to use Remix.
1. Create Streamr canvas to interact with realtime data stream and smart contract
    * Here is the [link](https://www.streamr.com/canvas/embed/8EJPdrh6TlaeSr7iat88kAJm-FI-jaTm6K-bHgtKe28A) to the canvas we have used for demo
    * Remember to change the GetContractAt module smart contract address with your deployed contract address
    * You can add Ethereum accounts in your Streamr Profile by pasting the private key from your Metamask account (IMPORTANT: use only expendable accounts, not your real personal one)
    * Here is [the link](https://github.com/streamr-dev/ruuvi-streamr) to the NodeJs library we used to push Ruuvi tag sensor data to Streamr Network via Raspberry Pi

You can find out more about Streamr API documentation at the following link http://streamrdev.com
For any technical related question feel free to join our Telegram group https://t.me/streamrdata or the IATA Hackathon dedicated forum.

  
