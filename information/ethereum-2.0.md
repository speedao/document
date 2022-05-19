---
description: WRITTEN BY Andrey Belyakov May 26, 2020
---

# Ethereum 2.0

**▼What is Ethereum 2.0?**

&#x20; Ethereum 2.0, also called Eth2, refers to a set of upgrades that will make Ethereum more scalable, more secure, and more sustainable.&#x20;

&#x20; _More information about Ethereum 2.0:_ [_What is Ethereum 2.0?_](https://consensys.net/blog/blockchain-explained/what-is-ethereum-2/) _&_ [_The Ethereum 2.0 Glossary_](https://consensys.net/knowledge-base/ethereum-2/glossary)_._

****

**▼What is the difference between Ethereum 1.0 and Ethereum 2.0?**

&#x20; There are **two primary improvements** introduced by Ethereum 2.0 that do not exist in Ethereum 1.0: Proof of Stake and Shard Chains.

&#x20; **Proof of Stake:** Currently, Ethereum 1.0 runs on a consensus mechanism known as Proof of Work (PoW). PoW relies on physical computing power (miners) and electricity (work) to build blocks on the blockchain. Proof of Stake (PoS) is an upgrade which enables improved security, scalability, and energy efficiency. Instead of relying on physical miners and electricity, PoS relies on validators (virtual miners) and deposits of ether. See “What is Proof of Stake” FAQ for more detail.

&#x20; **Shard Chains:** Shard chains are a scalability mechanism which drastically improves the throughput of the Ethereum blockchain. Currently, having a single chain made up of consecutive blocks is incredibly secure and makes information easy to verify. However, requiring each full node to process and validate each transaction in consecutive blocks can affect the ability to process transactions quickly – especially in times of high mainnet activity. Shard chains are a mechanism through which the Ethereum blockchain is “split” – thus dividing the data processing responsibility among many nodes. This allows for transactions to be processed in parallel rather than consecutively. Each shard chain is like adding another lane to upgrade Ethereum from a single lane road to a multiple lane highway.  More lanes and parallel processing leads to much higher throughput.

&#x20; _****  More information about Proof of Stake & Shard Chains:_ [_**What is Ethereum 2.0?**_](https://consensys.net/blog/blockchain-explained/what-is-ethereum-2/) _&_ [_**What is Proof of Stake?**_](https://consensys.net/blog/blockchain-explained/what-is-proof-of-stake/)

&#x20;&#x20;

**▼ What is the Ethereum 2.0 roadmap? What are the phases of Ethereum 2.0?**

&#x20; ****  As Ethereum 2.0 is a series of upgrades, rolling out in phases.

&#x20; **The Beacon Chain**: In December 2020, the first phase of Ethereum 2.0, the new Proof of Stake consensus layer, also called the “Beacon Chain,” was implemented. Each validator represents 32 ETH staked on the Beacon Chian. There are currently 222,052 validators for a combined 7,105,596 ETH. The Ethereum Proof of Work chain still continues to run alongside the new Ethereum PoS chain, ensuring there is no break in data continuity.

&#x20; **The Merge:** The current Ethereum Mainnet will soon merge with the Proof of Stake Beacon Chain. The merge will turn on Proof of Stake and end energy-intensive Proof of Work. Transactions and applications will still continue as normal on Ethereum, maintained by the same software clients we use today. In this sense, the terms Eth1 and Eth2 actually represent different layers of the stack: execution and consensus. &#x20;

* _Execution clients (Eth1 clients)_. Responsible for transaction bundling, execution, and state management. This layer is already represented by clients that Ethereum uses daily, such as Geth, OpenEthereum, Hyperledger Besu, and Nethermind.&#x20;
* _Consensus clients (Eth2 clients)_. Responsible for the validating blocks, also known as the Beacon Chain. This consensus-layer has been running smoothly for more than 6 months, with 155,663 validators collectively staking 4,981,046 ETH. Client teams include Teku, Lighthouse, Nimbus, and Prysm.

&#x20; The Merge is expected to happen in Q1/Q2 2022.&#x20;

&#x20; **Shard Chains**: The scalability phase of Eth2 will likely launch in late 2022. Shard chains will give Ethereum more capacity to store and access data, but they won’t be used for executing code.

&#x20; What the Eth2 development community didn’t anticipate was just how quickly Layer 2 solutions like Rollups would advance in 2021. Rollups are a Layer 2 technology that takes much of the burden of computation and storage out of the blockchain, and uses the chain just enough to benefit from its security guarantees. Rollups are now a key part of Ethereum 2.0’s scalability roadmap.

&#x20; _More information about the Ethereum 2.0 roadmap:_ [_Charting the Path to Proof of Stake Ethereum_](https://consensys.net/blog/blockchain-explained/charting-the-path-to-proof-of-stake-ethereum/)_,_ [_The Ethereum 2.0 Beacon Chain is Here. Now What?_](https://consensys.net/blog/blockchain-explained/the-ethereum-2-0-beacon-chain-is-here-now-what/)

****

**▼What will change when Ethereum 2.0 is completed? What will the improvements mean?**

&#x20; ****  Ethereum 2.0 will primarily benefit the scalability, throughput, and security of the Ethereum public mainnet. Ethereum 2.0 will not eliminate any of the data history, transaction records, or asset ownership of the Ethereum 1.0 chain.&#x20;

* _99.95% more energy efficient_: Carl Beekhuizen at the Ethereum Foundation estimates Proof of Stake will no longer require a country’s worth of power to secure the network.&#x20;
* _More validators, more decentralization_: Proof of Stake reduces the technical barriers for anyone to stake and help secure the network.
* _Improved security guarantees_: The ability to compromise the network will be magnitudes more expensive with Proof of Stake, not to mention that a 51% attacker is identifiable with validator addresses, and can be forked away from the network in the event of an attack.&#x20;

&#x20; _More information about the distinctions between 1.0 and 2.0:_ [_What is Ethereum 2.0?_](https://consensys.net/blog/blockchain-explained/what-is-ethereum-2/)



**▼What will happen to the current Ethereum “1.0” chain?**

&#x20; ****  Transactions and applications will still continue as normal on Ethereum, maintained by the same software clients we use today. In this sense, the terms Eth1 and Eth2 actually represent different layers of the stack: execution and consensus. &#x20;

* _Execution clients (Eth1 clients)_. Responsible for transaction bundling, execution, and state management. This layer is already represented by clients that Ethereum uses daily, such as Geth, OpenEthereum, Hyperledger Besu, and Nethermind.&#x20;
* _Consensus clients (Eth2 clients)_. Responsible for the validating blocks, also known as the Beacon Chain. This consensus-layer has been running smoothly for more than 6 months, with 155,663 validators collectively staking 4,981,046 ETH. Client teams include Teku, Lighthouse, Nimbus, and Prysm.



▼**What is the release date of Ethereum 2.0?**

&#x20; ****  The Proof of Stake [Beacon Chain](https://beaconcha.in/) launched in December 2020. The Merge combining Mainnet Ethereum and the Beacon Chain is expected in Q1/Q2 2022.&#x20;

&#x20; _More information about the Ethereum 2.0 roadmap:_ [_Charting the Path to Proof of Stake Ethereum_](https://consensys.net/blog/blockchain-explained/charting-the-path-to-proof-of-stake-ethereum/)



▼**What is Ethereum Proof of Stake?**

&#x20; ****  Proof of Stake (PoS) is an upgrade from Ethereum 1.0’s current Proof of Work consensus model and allows for improved security and scalability. PoS is a consensus mechanism that relies on validators and staked ETH for the continuation of blocks on the blockchain, and is necessary for sharding. Validators are people who elect to continue the blockchain by depositing (or “staking”) 32 ETH into the deposit contract. On a continuous basis, validators are randomly selected from the pool of all validators to be given the opportunity to create the next block. Should a validator successfully validate a block, they will receive an ETH reward. If a validator attempts to compromise the truthful continuation of the blockchain, their deposit will be ‘slashed’ – meaning they will lose some or all of their 32 staked ETH.

&#x20; A Proof of Stake mechanism offers more crypto-economic security compared to the more abstract disincentive of losing the cost associated with electricity. Rather than investing in an enormous mining facility to defray the cost of electricity to mine blocks in PoW, staking on Ethereum 2.0 will only require a consumer laptop (some software clients aim to be lightweight enough to run on a cell phone, thus reducing the barrier to entry to participating in the consensus process, consequently increasing the decentralization of the network).&#x20;

&#x20; The Proof of Stake Beacon Chain is now live, with 222,052 validators staking a combined 7,105,596 ETH (as of Sept 1, 2021).

&#x20; _More information about Proof of Stake:_ [_The State of Staking (August 2021)_](https://consensys.net/blog/codefi/the-state-of-staking-in-august-2021/)_,_ [_Codefi Staking_](https://consensys.net/codefi/staking/)

****

**▼Can I “buy” Ethereum 2.0 ether?**

&#x20; ****  There is no way to buy Ethereum 2.0 ETH, since there will not be a new type of ETH token. There are two ways ETH holders can participate and earn rewards for staking on Ethereum 2.0. First, an ETH holder may run their own validator(s) by staking ETH in increments of 32 on the network. Running your own validator node means you have the responsibility to validate and organize blocks – not doing so could result in a penalty of ETH.&#x20;

&#x20; Another option for ETH holders is to stake their rewards through a staking provider like [ConsenSys Codefi](https://consensys.net/codefi/staking/) or join a staking pool with smaller amounts of ETH, through which anyone can stake whatever small amount of ETH they are able to and still receive rewards proportional to their contribution.

&#x20; _More information about staking on Ethereum 2.0:_ [_What Happens to my ETH on Ethereum 2.0?_](https://consensys.net/blog/blockchain-explained/what-happens-to-my-eth-on-ethereum-2/)_,_ [_My Journey to Becoming a Validator on Ethereum 2.0_](https://consensys.net/blog/blockchain-explained/my-journey-to-becoming-a-validator-on-ethereum-2-0/)



▼**How can I become a validator for Ethereum 2.0?**

&#x20; ****  The Beacon Chain was the first step toward changing the consensus mechanism of Ethereum from Proof of Work to Proof of Stake. With Proof of Stake, validators commit a stake and run software to secure the consensus layer of Ethereum.&#x20;

&#x20; More technical users can run their own validator node and stake their own ETH. [Codefi Activate](https://activate.codefi.network/)worked with the [Ethereum Foundation](https://ethereum.org/) to build the [Launchpad app](http://launchpad.ethereum.org/), to provide technical onboarding to the requirements, responsibilities, and risks in becoming an Eth2 validator. Visit the Launch Pad to learn more about becoming a validator on the Beacon Chain.

&#x20; Another option is to stake your ETH using a staking provider like [Codefi Staking](https://consensys.net/codefi/staking/). There will be both custodial and non-custodial staking services offered.

&#x20; _To learn more about running your own validators on Ethereum 2.0, visit_ [_Codefi Activate_](https://activate.codefi.network/) _or check out_ [_My Journey to Becoming a Validator on Ethereum 2.0_](https://consensys.net/blog/blockchain-explained/my-journey-to-becoming-a-validator-on-ethereum-2-0/)



▼**How do you get rewarded for staking on Ethereum 2.0?**

&#x20; As a validator on Ethereum 2.0, you get rewarded for proposing and attesting the next block in the chain. You will receive rewards in ETH for making valid proposals and attestations.

&#x20; Rewards are dynamically calculated based on the state of the network upon epoch completion. Network level reward issuance rates are a function of the total amount of ETH staked and average % online of validator(s). Individual validator reward rates depend on the number of validators run and % uptime of the validator.

&#x20; Rewards minus penalties are transferred to validators every epoch (384 seconds \~6.5 minutes). As a result, the reward you expect to receive when being randomly selected to be a validator may be different than what a validator actually receives. Check out the [Ethereum 2.0 Calculator](https://docs.google.com/spreadsheets/d/15tmPOvOgi3wKxJw7KQJKoUe-uonbYR6HF7u83LR5Mj4/edit#gid=1548910165)for an idea of the types of rewards for staking on Ethereum 2.0.

&#x20; Another option is to stake your ETH using a staking provider like [Codefi Staking](https://consensys.net/codefi/staking/). There will be both custodial and non-custodial staking services offered.

&#x20; _More information about rewards on Ethereum 2.0:_ [_What is Proof of Stake?_](https://consensys.net/blog/blockchain-explained/what-is-proof-of-stake/) _&_ [_The Eth2 Calculator_](https://docs.google.com/spreadsheets/d/15tmPOvOgi3wKxJw7KQJKoUe-uonbYR6HF7u83LR5Mj4/edit#gid=1548910165)

▼**What is the official Ethereum 2.0 deposit contract address?**

&#x20; ****  In December, the Beacon Chain launched, which established the Proof of Stake consensus mechanism. If you want to run your validator on Ethereum 2.0, you can make sure you have the necessary hardware requirements, technical expertise, and follow step-by-step instructions using the official [Ethereum Launchpad](http://launchpad.ethereum.org/).&#x20;

&#x20; With the highly anticipated launch of the first phase of Eth2, we expect attempts to scam users into depositing ETH into fake addresses. For that reason, we recommend checking the address listed on this page with other trustworthy sources such as the Ethereum Foundation, [Etherscan](https://etherscan.io/), and [ConsenSys](https://consensys.net/knowledge-base/ethereum-2/).&#x20;

&#x20; Deposit Contract Address: [0x00000000219ab540356cbb839cbe05303d7705fa](https://etherscan.io/address/0x00000000219ab540356cBB839Cbe05303d7705Fa)

&#x20; **WARNING: DO NOT SEND ETH TO THIS CONTRACT.** Sending Eth to this contract address will result in a failed transaction, and does not mean you are staking on Eth2.



▼**What are the risks of staking ETH and becoming a validator on Ethereum 2.0?**

&#x20; ****  An upside to participating as a validator is that you can earn rewards of ETH. There is, however, a risk of losing funds through the ‘slashing’ of the ETH you staked on the network. With a small amount of care, this risk is negligible. The first way a validator might lose funds is by being offline and not performing its duties correctly. This incurs a relatively mild penalty: roughly the same as the reward you could have made. As long as you are currently participating for at least 50% of the time, you will not lose your stake. The other way a validator can lose funds is to publish contradictory information about the chain. In this case, the validator is slashed and ejected from the system. The amount slashed is between 1 ETH and the entire stake amount, depending on other factors. Being slashed is easy to protect against and ought never to happen unless a validator is deliberately acting maliciously.

&#x20; _More information about risk incentives on Ethereum 2.0:_ [_**What is Proof of Stake?**_](https://consensys.net/blog/blockchain-explained/what-is-proof-of-stake/)

****

**▼How do I get selected to propose and attest a new block on the Beacon Chain?**

&#x20; ****  After you have registered your 32 ETH stake in the deposit contract and your validator has become active, it will be assigned duties from time to time by the Beacon Chain. Validators will be called on to attest to blocks on the Beacon Chain once every 6.4 minutes (once per epoch), and randomly selected from the whole validator set to propose blocks periodically. If there are 100,000 validators in total, your validator will be asked to propose a block about once every two weeks on average. This is all completely automatic and entirely handled by the validator software.

&#x20; _More information about attesting blocks on the Beacon Chain:_ [_**What is Ethereum 2.0?**_](https://consensys.net/blog/blockchain-explained/what-is-ethereum-2/)



▼**What will happen to the ETH I own now?**

&#x20; ****  There is no need to do anything special with the ETH you currently own. It continues to be fully usable on Ethereum even after the merge to Proof of Stake.

&#x20; _More information about ETH:_ [_What Happens to my ETH on Ethereum 2.0?_](https://consensys.net/blog/blockchain-explained/what-happens-to-my-eth-on-ethereum-2/)



**▼Who is developing Ethereum 2.0?**

&#x20; ****  Hundreds of people! The work is largely led and coordinated by the Ethereum Foundation research team, but many other research and implementation teams are making substantial contributions. The main work is to collaborate on defining the specification for Ethereum 2.0, which is maintained on the[ Ethereum Foundation GitHub pages](https://github.com/ethereum/eth2.0-specs). Five independent teams are building Ethereum 2.0 clients in a variety of different programming languages for different use cases and are constantly feeding back into the design and specifications. ConsenSys Quorum is building [Teku](https://consensys.net/knowledge-base/ethereum-2/teku/), which is written in Java and maintained by the same team behind Hyperledger Besu.

&#x20; _More information about the people behind Ethereum 2.0:_ [_**What’s New in Eth2?**_](https://hackmd.io/@benjaminion/eth2\_news)



**▼What does Vitalik Buterin think of current Ethereum 2.0 progress?**

&#x20; ****  Vitalik tweeted out his thoughts on the progress and roadmap of Ethereum 2.0. See his thoughts on [the next 5-10 years of Ethereum.](https://twitter.com/vitalikbuterin/status/1240365047421054976?lang=en)



**▼Where can I learn more about Ethereum 2.0?**

&#x20; ****  There are tons of resources for both technical and non-technical people interested in keeping up with Ethereum 2.0 developments.

&#x20; If you haven’t already, check out [**ConsenSys’ Ethereum 2.0 Knowledge Base**](https://consensys.net/knowledge-base/ethereum-2) – a complete library of resources and product information about Eth2, Proof of Stake, and staking services.

&#x20; To keep up with regular updates regarding Ethereum 2.0, some good general resources are:[ What’s New in Eth2](https://eth2.news/),[ EthResear.ch](https://ethresear.ch/) and[ EthHub](https://ethhub.io/).



**▼What is the history of upgrades to the Ethereum blockchain?**

&#x20; ****  Ethereum has undergone four planned upgrades since its public mainnet launch in July 2015 (called “Homestead”). In order the four upgrades were: Homestead (March 2016), Metropolis Byzantium (October 2017), Metropolis Constantinople (February 2019), and Istanbul (December 2019). Together, these upgrades improved the functionality of the Ethereum 1.0 chain while setting the stage for Ethereum 2.0

&#x20; _More information about the people behind Ethereum 2.0:_ [_**A Short History of Ethereum**_](https://consensys.net/blog/blockchain-explained/a-short-history-of-ethereum/)

\
