# PI-Blockchain Chain Specification
*BY SIGMA PI DELTA TECHNOLOGIES*

Chain specification for PI Blockchain.

Pi Blockchain Smart Contracts (https://github.com/sigma-pi-delta/pi-blockchain/smart-contracts.git) are allocated in genesis block. 
Any consensuated change in the behaviour of this contracts requires to start a new blockchain starting with previous state in the new genesis block.

After Pi Blockchain was launched the community has voted for two changes:

## FORK 1
On each block collected rewards were sended 50% to node holders and 50% removed from circulation. As when interacting with Emisor contract half of the commission is removed from circulation community decided to make a change and stop removing from circulation again and send 100% of the rewards to node holders.

## FORK 2 (Current)
Community voted a change in Emisor behaviour. The change allows to validators to make Pi/Token inclusion/extraction with a previous voted rate of exchange.
