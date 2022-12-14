# 1   
Today I an going to talk about blockchain basics. Let's start by asking ourselves, what is a blockchain? Why should you care about it?   
# 2   
Unlike traditional methods, blockchain enables **peer to peer transfer of digital assets** without any intermediaries.   
# 3   
The blockchain by itself has taken a life of its own and permeated a broad range of applications across many industries, including finance, healthcare, government, manufacturing, and distribution. The blockchain is poised to innovate and transform a wide range of applications, including goods transfer, for example, supply chain. Digital media transfer, for example, sale of art. Remote services delivery, example, travel and tourism. Distributed intelligence, example, education credentialing. Distributed resources, for example, power generation and distribution. And government public records and open governing.   
# 4   
Moreover, blockchain can enable an inclusive economy. It can enable a person in a remote corner of the world to partake in a democratic process. Opportunities for innovative applications are endless. There is a dire need for critical thinkers, designers and developers who can envision and create newer application models on blockchain to benefit the world. (2:10)   
# 5   
Bitcoin is not the only player in town. But blockchain was a technology originally created to support the famous cryptocurrency, BitCoin. Though our focus is on a general blockchain, we've to understand the working of the technology behind Bitcoin to fully appreciate the innovation of blockchain. So let's begin with an introduction of Bitcoin.   
# 6   
Two major contributions of cryptocurrency Bitcoin are a continuously working digital currency system, and a model for autonomous decentralized application technology called the blockchain.   
# 7   
Bitcoin enabled an innovative platform for peer to peer transfer of value without any central authority.   
With no central authority, how did Bitcoin realize trust and security?   
# 8   
Let's consider a scenario that a system where peers can transact directly with each other irrespective of where they are located.   
We have A novel infrastructure called the blockchain.   
Peers are not necessarily known to each other.   
This is a decentralized system. How do we establish trust among the peers in such a decentralized system?   
Now I'll explain it using by a game.
A is lending B $10,000. This is one single peer to peer transaction. A and B both make a note of it on a ledger.
What if A change their entry from 10,000 to 11,000? Alternatively, B changes their`s from 10,000 to 1,000. To prevent this trust violation, we need to seek the help of people around us, you can get a valid copy of this ledger.
# 9   
By having a process in place to validate, verify, and confirm transactions. Record the transaction in a distributed ledger of blocks, create a tamper-proof record of blocks, chain of blocks, and implement a consensus protocol for agreement on the block to be added to the chain. So, validation, verification, consensus, and immutable recording lead to the trust and security of the blockchain. (10min)   
# 10   
# 11   
Here is the basic structure of a blockchain.   
Transaction is the basic element of the Bitcoin Blockchain. Transactions are validated and broadcast.   
Many transactions form a block. Many block form a chain through a digital data link. Chosen block is verified, and added to the current chain.   
Validation and consensus process are carried out by special peer nodes called miners.   
# 12   
Let's now discuss the details of a single transaction in bitcoin. A fundamental concept of a bitcoin network is an Unspent Transaction Output, also known as UTXO.   
The set of all UTXOs in a bitcoin network collectively defined the state of the Bitcoin Blockchain.   
UTXO's are referenced as inputs in a transaction.   
UTXO's those are also outputs generated by a transaction.    
All of that UTXO's is in a system, are stored by the participant nodes in a database.   
Now let's review the role of the UTXO's in a Bitcoin Blockchain. The transaction uses the amount specified by one or more UTXOs and transmits it to one or more newly created output UTXOs, according to the request initiated by the sender.   
# 13   
The structure of a given UTXO is very simple. It includes a unique identifier of the transaction that created this UTXO,    
an index or the position of the UTXO in the transaction output list,    
a value or the amount it is good for.    
And an optional script, the condition under which the output can be spent.   
# 14   
The transaction itself includes a reference number of the current transaction,   
references to one no more input UTXOs,   
references to one or more output UTXOs newly generated by the current transaction,   
and the total input amount and output amount.   
# 15   
For the block structure, because of the limited time, I just provide a site for you to explor.   
# 16   
Now that we have reviewed the basics of a blockchain and its basic structure and origin, let's consider the basic operations in a blockchain.   
# 17   
Operations in the decentralized network are the responsibility of the peer participants and their respective computational nodes. For example, laptop, desktop, and server racks.   
# 18   
First, we have to discuss the participants. There are two major roles for the participants.   
Participants that initiate transfer of value by creating a transaction,   
additional participants called miners, who pick on added work or computation   
# 19   
You might wonder why participant would take on additional work.   
Well, the miners are incentivised with bitcoins for the efforts in managing the blockchain, as we'll find out.   
Transaction validation is carried out independently by all miners.   
# 20
invalid transactions are rejected and will not be broadcast. All the valid transactions are added to a pool of transactions. Miners select a set of transaction from this pool to create a block.   
This creates a challenge. If every miner adds the block to the chain, there will be many branches to the chain, resulting in inconsistent state. Because the blockchain is a single consistent linked chain of flux. We need a system to overcome this challenge.   
# 21   
The solution is, Miners compete to solving a puzzle to determine who earn the right to create the next block. In the case of bitcoin blockchain, this parcel is a computation of parcel and the central processing unit or CPU intensive. Once a miner solves the puzzle, the announcement is broadcast to the network and the block is also broadcast to the network. Then, other participant verify the new block. Participants reach a consensus to add a new block to the chain. This new block is added to their local copy of the blockchain. Thus, a new set of transactions are recorded and confirmed.   
The algorithm for consensus is called proof-of-work protocol, since it involves work a computational power to solve the puzzle and to claim the right to form the next block.   
Transaction zero, index zero of the confirmed block is created by the miner of the block. It has a special UTXO and does not have any input UTXO. It is called the coinbase transaction that generates a minor's fees for the block creation.   
# 22
In the next section, I am going to talk about Privacy, Cryptography and Algorithm in blockchain begining with a classic problem called 3-colorable Graphs, it is np-complete and it have zero knowledge proof.   
I will explain zero know proof using this video. And I will provide an article about how to solving 3 coloring problem using zero-trust and it`s implication in blockchain.
# 23
And Last I want to talk a litter bit more about uniswap.