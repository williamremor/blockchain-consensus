# Serialization of Proof-of-work Events: Confirming Transactions via Recursive Elections

Utilizes a combination of PoW and DAGs to reach scalable consensus. In SPECTRE, the blocks are mined pointing to multiple parents, not just one, so the network could potentially handle multiple blocks per second. Mining a block pointing to some parent blocks supports those blocks validity. Compared to PoW’s “longest chain wins”, SPECTRE uses something like “blocks with the most childen win.” SPECTRE hasn’t been battle-tested in the wild yet, and new attack vectors are likely to emerge, but it feels like a very clever potential way to fix Bitcoin.

#### Used in

* Proposal for Bitcoin [https://bitcoin.org/en](https://bitcoin.org/en)

### Proof-of-work \(PoW\) / High Interest Proof of Stake \(HiPoS\)

Coin combining PoW and HiPoS

#### Used in

* EdgeCoin \(EDGE\)
