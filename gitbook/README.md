---
description: NFT Collectibles and Tokenomics
---

# 💡 Space Belters White Paper (Draft)

**1. Introduction**

Space Belters is a cutting-edge NFT-based collection set in an imaginative, futuristic world. As humanity reaches the Kardashev Scale Type 1 Civilization and stands on the cusp of constructing the first-ever space elevator, the Space Belters collection invites collectors to own unique characters that embody the spirit of innovation and exploration. The characters, known as "Belters," are the pioneers who participate in building the space elevator, leading the way in space exploration and discovery. In addition to the NFT collectibles, the Space Belters ecosystem introduces an ERC20 token backed by eth to reward NFT holders and provide additional utilities within the project

**1.1. Background**

The concept of the space elevator has captured the imagination of many, including scientists, engineers, and dreamers. A space elevator is a hypothetical structure that could transport people and objects from the surface of the Earth to space without the need for rockets. A space elevator would revolutionize access to outer space, dramatically reducing the cost and environmental impact of space travel. The Space Belters collection takes inspiration from this exciting concept, offering unique NFTs that allow collectors to join the journey and embody the spirit of innovation and  exploration.&#x20;

**1.2. Collection Overview**

The Space Belters collection features 10,000 unique ERC721 NFTs, each representing a distinctive character within the Tiamat Universe. As collectors acquire and trade these NFTs, they can stake them in the Space Elevator smart contract, earning ERC20 tokens as rewards and contributing to the construction of the space elevator.

**1.3. Staking and Rewards**

The Space Belters project introduces an innovative staking mechanism that allows collectors to participate in the space elevator's construction by staking their NFTs. Through staking, collectors can earn ERC20 tokens as rewards, which can be used to enhance the value of their NFTs. When the contract is empty of tokens, the space elevator's construction is complete, symbolizing a significant milestone in the Space Belters universe. At this point, new possibilities will open up, and the team will explore new expansions and opportunities for the Space Belters ecosystem.

**1.4 Contracts Overview**

The Space Belters ecosystem comprises various smart contracts to manage different aspects of the project:

ERC721 Collection Contract: This contract governs the creation, ownership, and transfer of the unique Space Belter NFTs.

ERC20 Token Contract: This contract manages the Space Belters ERC20 token and stores the ETH that backs the token. The token is used to reward NFT stakers and can be swapped back for ETH at any time. All tokens are burned when sent to the ERC20 contract and the NFT upgrade contract, reducing supply, and increasing the value of the token.

NFT Staking Contract: This contract allows NFT holders to stake their NFTs and receive ERC20 tokens as rewards based on the NFT's level. The rewards system increases based on the exponential function of 10\*(1.05^level-1). All tokens start in the Staking Contract and can only be earned by the staking of Space Belter NFT's.

NFT Upgrade Contract: This contract enables NFT holders to upgrade their NFTs by burning ERC20 tokens, thus reducing the token supply and increasing the value of both the NFTs and the remaining tokens. The contract keeps a mapping of all levels by tokenID. The upgrade cost system increases based off the exponential function of 10\*(1.1^level-1).

In addition to these contracts, the Space Belters project includes an automatic transfer system for the 5% royalties and market sales of the NFT collection into the ERC20 Token Contract. This is done by setting the token contract address as the receiver of fees in the NFT collection contract. The ERC20 Token Contract will hold these funds to provide value for the token. At any time, the token can be sent back to the ERC20 contract for eth at a value of eth in contract / totalSupply of tokens. A function exists that can enable minting. To prevent people power leveling to 60 by buying tokens, this feature will start disabled. At a later date, eth can be sent to the contract for ERC20 tokens at a value of 1000 tokens for 1 eth, for a token value of 0.001 eth.&#x20;

#### 1.5 Tokenomics and Fund Allocation ( DRAFT )

All tokens will be sent to the Staking Space Elevator Contract to reward NFT stakers. The token rewards from staking are based on the level of the NFT, which can be upgraded by burning tokens at the NFT Upgrade Contract, reducing the token supply and increasing the value of the NFT based off the NFTs cost of production (sum of all tokens used to upgrade it to current level) and the amount of rewards that the NFT's receive per hour. Additionally, the remaining token value is increased in ETH for every NFT that is upgraded because the tokens are burnt when upgrading, reducing supply of tokens.

At any time, tokens can be sent back to the ERC20 Token Contract for a percentage of the ETH in the contract. The ETH amount returned per token is determined by dividing the ETH in the contract by the total supply of tokens (which reduces as tokens are spent and burnt on upgrades). This creates a price floor in ETH for the tokens since they can always be sent back to the contract for a minimum amount of ETH.

In addition to the ability to send tokens back to the ERC20 Token Contract for a percentage of ETH, the contract includes a minting feature that allows for more tokens to enter the ecosystem. To prevent people power leveling to 60 by buying tokens, this feature will start disabled. However, as more people level up to 60, or the total balance of eth in the contract starts getting low, minting will be enabled. When a user sends ETH to the contract, tokens are returned at a rate of 1000 tokens per 1 eth. By setting a high minting price, this encouragers players to get cheaper tokens by participating in the Space Elevator construction with a Space Belter and upgrading their NFT, and discourages whales from minting a large amount of supply as the premium on minting is very high compared to the initial token swap back value (depending on eth and total supply of token). Eventually price may stabilize around this point of 0.001 eth per token assuming 327,829,803.50 tokens are spent/burnt by all 10,000 space belters leveling up to level 60 and a contract balance of 170.1965 eth. Other token burn mechanics/spending options may be introduced to help achieve maximum token burn to increase the value of the token.&#x20;

As more players level up their NFTs, more tokens are burnt, increasing the value of the token in ETH and the NFT. Token values in ETH and rewards start slow, as the initial token value is calculated as 425 ETH received from minting the NFT's is divided by 328 million tokens creating a starting price of 0.00000129573 ETH. However, as the number of tokens decreases due to burning and spending, the token value increases in eth, as the calculation becomes 425 ETH divided by a reducing token supply as tokens are burnt on upgrades.

Additionally, 5% of royalties and market sales of our NFT collection will be deposited into the ERC20 Token Contract. As NFTs are traded, more value is added to the token. The platform will also charge a 5% fee, which will be directed to the same contract, further supporting the token's value.

As the ERC721 collection is traded on NFT markets, the royalties and platform fees will add to the ETH amount in the contract.

The token value in eth will vary based off the amount of ETH in the contract and the total supply of tokens. The amount of ETH will increase as eth is deposited and tokens are minted. It will also increase based off rewards deposited from royalty fees, and decrease when tokens are redeemed for eth. Total supply of tokens will increase as they are minted with ETH, with 1000 tokens minted per eth, increasing both the total amount of tokens and the amount of eth in the contract. Tokens will reduce based off amount of tokens spent/burned on upgrades, and amount of tokens redeemed/burned for ETH.&#x20;

#### Revised Roadmap and Milestones

The Space Belters project has a clear and exciting roadmap designed to keep collectors engaged and continuously offer new opportunities for involvement in the Tiamat Universe. The revised roadmap incorporates the changes outlined above and is divided into various stages, each representing a milestone in the development of the Space Belters collection and ecosystem.

#### 2.1. Stage 1: Genesis NFT Release

The first stage of the roadmap focuses on the Genesis NFT minting of the Space Belters. During this stage, collectors can purchase and trade their unique NFTs, representing their characters in the Tiamat Universe.&#x20;

#### 2.2. Stage 2: Space Elevator Staking, NFT Upgrades and Token Burning

During this stage, players can stake their NFTs in the Space Elevator Staking Contract, contributing to its construction and earning ERC20 tokens as rewards based on the level of their NFTs. These rewards can be used to upgrade the level of their NFT, which not only enhances its value but also reduces the overall token supply, increasing the value of the remaining tokens in ETH. NFT holders can also upgrade their NFTs by burning ERC20 tokens through the NFT Upgrade Contract, which allows for further increases in staking rewards for each level gained.

**2.3. Stage 3: The Race to Level 60**

In this stage, the Space Belters team will introduce a dapp that keeps track of the highest level NFTs by tokenID and displays a leaderboard of "The Race to Level 60". The top finishers in the race will receive a reward in ETH and an exclusive NFT drop. This will incentivize collectors to level up their NFTs and create a competitive atmosphere within the community to complete construction of the space elevator.&#x20;

#### 2.4. Stage 4: Token Level Gated Content

As players gain in levels, we will implement token level gated content. This content will require a certain token level to participate in and complete successfully. Endgame content will require the maximum level of a level 60 Space Belter NFT with high DPS (staking per hour).

#### 2.5. Stage 5: Future Developments and Innovations

With a strong community and a growing ecosystem, the Space Belters project will continue to introduce new features, upgrades, and innovations based on community feedback and market trends. This stage will ensure that the Space Belters collection remains relevant, engaging, and valuable for collectors. Potential developments may include new staking opportunities, utilities for the ERC20 token, and integration with decentralized finance (DeFi) platforms.

**3. Technical Aspects**&#x20;

To ensure the smooth functioning of the Space Belters ecosystem and provide collectors with a seamless experience, the project is built using industry-standard technologies and token standards.

**3.1. ERC721 NFTs**

Each Space Belter NFT is created using the ERC721 token standard, which is the widely accepted standard for non-fungible tokens on the Ethereum blockchain. This standard ensures that each NFT is unique, indivisible, and easily tradable on various NFT marketplaces.

**3.2. ERC20 Reward Tokens**

When collectors stake their Space Belter NFTs in the Space Elevator smart contract, they are rewarded with ERC20 tokens based off the level of the NFT. These tokens can be used within the Space Belters ecosystem to enhance the value of their NFTs.

**3.3. Token Distribution and Supply**

The total supply of ERC20 tokens is designed to be limited, ensuring scarcity. The entire supply is deposited to the staking contract, to be distributed by NFT staking at the Space Elevator contract. The total supply is calculated by taking the total cost of upgrading a single NFT to level 60, then multiplying by the number of NFT's in the collection, and then rounding up to the nearest million.&#x20;

**3.4. Smart Contracts and Security**

The Space Belters project utilizes smart contracts to manage the staking of NFTs and distribution of ERC20 tokens. These smart contracts are designed to be secure, efficient, and reliable, ensuring the safety of collectors' assets and the smooth operation of the Space Belters ecosystem.

**4. Marketing and Growth Strategy**

To increase awareness of the Space Belters project and attract a diverse community of collectors and enthusiasts, the team will implement a multifaceted marketing and growth strategy.

**4.1. Social Media and Influencer Partnerships**

The Space Belters team will leverage social media platforms, such as Twitter, Instagram, and Discord, to share news, updates, and engaging content related to the project. The team will also collaborate with influencers and key opinion leaders within the NFT and crypto space to expand the project's reach and attract new collectors.

**4.2. Community Engagement and Contests**

To foster a strong and active community, the team will regularly organize events, contests, and giveaways. These activities will not only reward existing community members but also attract new collectors to the project.

**4.3. Collaborations and Cross-Promotions**

Space Belters will actively seek partnerships with other NFT projects, artists, and relevant organizations to create unique, co-branded content and experiences. These collaborations will enhance the value of Space Belters NFTs and help expand the project's reach within the wider NFT ecosystem.

**4.4. Traditional and Digital Media**

In addition to leveraging social media and influencer partnerships, the team will also explore opportunities to promote the project through traditional and digital media channels, such as press releases, blogs, podcasts, and interviews.

**5. Future Development and Expansion**

The Space Belters team is dedicated to the continuous improvement and expansion of the project. By actively engaging with the community and gathering feedback, the team will identify new opportunities and challenges, ultimately shaping the future direction of the project.

**5.1. New Staking Opportunities and Utilities**

As the Space Belters universe evolves, the team will introduce new staking opportunities and utilities for both the ERC721 NFTs and the ERC20 tokens. This may include additional smart contracts, rewards, and exclusive features for holders of the Space Belters NFTs and tokens.

**5.2. Integration with Decentralized Finance (DeFi) Platforms**

The project will explore opportunities to integrate Space Belters NFTs and tokens with existing DeFi platforms, offering collectors additional ways to utilize and benefit from their holdings.

**5.3. Potential Gaming and VR Expansions**

Depending on community interest and feedback, the Space Belters team may explore the possibility of expanding the project into gaming or virtual reality (VR) experiences. This could include developing mini-games, interactive experiences, or even a fully-fledged VR environment where collectors can interact with their NFTs and other players.

**5.4. Continuous Community Engagement**

The Space Belters team believes that the community is the foundation of the project's success. As such, they will continue to engage with collectors, solicit feedback, and implement community-driven ideas and improvements, ensuring that the project remains relevant, exciting, and valuable for years to come.

**Conclusion**

The revised Space Belters whitepaper incorporates critical changes, such as the inclusion of the ERC20 token, multiple smart contracts for different purposes, and an enhanced staking reward system based on NFT levels. These modifications aim to create a more engaging and interactive experience for collectors and enthusiasts alike. The updated roadmap reflects the project's dedication to continuous improvement, community engagement, and the pursuit of innovative opportunities within the Tiamat Universe.

&#x20;

By integrating unique digital art, a futuristic universe, and advanced staking features, the Space Belters project stands out in the NFT landscape. Through strategic partnerships, a commitment to innovation, and a strong focus on community building, the Space Belters project is poised to redefine the NFT experience and deliver a captivating journey for collectors and enthusiasts alike.
