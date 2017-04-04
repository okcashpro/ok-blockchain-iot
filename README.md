# OK Cryptocurrency Blockchain for Raspberry Pi, Pine64+ and IoT Devices [Instant Sync]

![OK-Blockchain](http://i.imgur.com/LLkiV14.jpg)

When you load the OK Wallet for the first time it connects to the peer-to-peer network and starts to synchronize the OK blockchain. 

### When to use the ok-blockchain-iot to Sync your OK wallet on your Raspberry Pi, Pine64+ and IoT devices

The first time sync of the OK blockchain can take quite a while; sometimes up to 72 hours depending on IoT device and Internet connection. 

With OK you can speed up this process by loading compressed backups of the OK blockchain. 

Adding the current ok-blockchain to your local okcash data directory speeds up the synchronization process which will get your wallet up and running in minutes.

### How to use the ok-blockchain to sync your OK wallet on your Raspberry Pi, Pine64+ and IoT devices.

1.- Close the OK Wallet and download the latest ok-blockchain-iot file from:
      https://github.com/okcashpro/ok-blockchain-iot/releases

2.- Place the ok-blockchain-arm.zip or ok-blockchain-arm64.zip file in the Okcash data directory.

3.- Unzip the ok-blockchain-arm.zip or ok-blockchain-arm64.zip file. (includes txleveldb folder + blk0001.dat files)

4.- Start your OK Wallet and give it some minutes to finish it's first time Sync process. 
(The client might be unresponsive but don’t worry - it’s just loading and verifying all the ok-blockchain-iot data)

### Okcash data directory

IoT devices:

**~/.okcash/**

## Live support by the community

If you require further assistance or want to keep informed of updates, join:

https://discord.io/okcash
