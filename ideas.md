# 黑客松想法

我们提供了这个黑客马拉松的想法清单，您可以选择一个想法，也可以自己构思一个产品来参加比赛。


## 去中心化金融

* 在NEAR上实现Uniswap，用NEAR来交易其他的fungible tokens (详情可见fungible token标准http://github.com/nearprotocol/neps/pull/21).
* 链上保险：例如，确保比特币价格在一定范围内（类似于衍生工具），提供一个报价的来服务于保险的供应商。可用Oracle预言机来提供解决事件的真相。

## 游戏

* 基于石头剪刀布的游戏，可以打怪或于其他玩家对打。角色是可升级的NFT，随着战斗的进行，它会随着时间的推移而不断提高等级。

## 社交

* 名片：向用户发送具有QR码的电子名片或纸质名片，可用其申请NFT。
* Moloch DAO: 基于Moloch游戏设计来实现一个DAO (https://molochdao.com/)
基于Moloch游戏设计实现DAO
* 微信小程序: 使用NEAR登录并与群中的其他用户交换NFT。
* 参加活动的NFT纪念品: 由活动组织者的提供的QR码，与会者扫描并拿到特定NFT纪念品。
* 提供给活动组织者和演讲者的Marketplace：组织者可以创建活动,提供活动地点和演讲席位。感兴趣参与演讲的人可以竞拍发言权，并让想参加活动的人投票。
* Maskbook类似的插件: 使用社交产品现有的API，并通过其网络扩展区块链的影响力。教育人们隐私为何重要以及区块链可以做什么。

## 企业和政府

NEAR可以通过私有分片来支持企业应用程序。
私有分片背后的主要思想是，公司可以运行自己的分片，在保留其数据隐私性的同时仍与公共链和其他私有分片上的应用程序进行通信。
与现有的联盟链相比，这不需要大笔前期资金和IT人员对专有系统的投入，只需要公司建立一个私有分片。

The ideas here are all about possible contracts that can interact between public and private shards. 
以下是一些基于公共和私有分片之间交互的智能合约的想法。

* 教育：使用私有分片为学生保持成绩和出勤率，公共分片包含可以利用此信息的各种应用程序。例如，奖学金是根据成绩定期颁发的。
* 供应链：跨越两个私有分片，传递有关交易的一个组建的信息，同时保持组件来源的证明。

## 其他

* 订外卖:区块链上的三方市场，它连接餐馆、配送员、和用户。当用户从指定的餐厅订餐，配送员可以在此这个市场上直接取单。
* 跟踪包裹：供应商通过用户的公钥加密包裹的跟踪信息，只有特定的用户才能解密并检查状态。
* 智能门票:创建智能的活动票证，以确保在票证的整个生命周期内监督，管理和粉丝间的沟通。限制黄牛恶意炒票和其他票务方面的欺诈。

# Hackathon Ideas 

This is list of ideas for hackathon, feel free to choose one or come up with your own.


## Finance 

* Uniswap for NEAR to fungible tokens (see for fungible token standard - http://github.com/nearprotocol/neps/pull/21).
* Basic insurance on chain: for example ensure Bitcoin price within some bounds (e.g. a derivative), have a market of offers and supplier of insurnace. Oracle that would provide the source of truth for resolving the event.

## Gaming

* Rock-paper-scissors based game to figth monsters or other players. The character is an upgradable NFT that improves over time as battles are carried out.

## Social

* Business card: send users a business card that has QR code they can claim NFT with. This can include paper cards as well.
* Moloch DAO: implement a DAO based on Moloch game design (https://molochdao.com/)
* Wechat Mini app: login with NEAR and exchange NFTs with other users in the group.
* NFT for attending meetup: QR code for meetup organizers that allows attendees to scan and claim the specific NFT of the specific event.
* Marketplace for meetup organizers and speakers. Organizers can create an event and offer slots for speakers. Speakers either use auction mechanic or offer to speak and have attendees vote for who to listen to.
* Maskbook like plugin:use the API of those social products already have and expand the influence of blockchain by their network. Educate people why privacy matters and what blockchain can do.

## Enterprise

NEAR has support for enterprise applications via private shard.
Main idea behind private shard is that a company can run their own shard, preserving privacy of the data on it while still communicating with applications on public chain and other private shards.
Compared to regular consortium chains, this doesn't require big buy in as just requires to spin up shard by given company first and already get benefits.

The ideas here are all about possible contracts that can interact between public and private shards.

* Education: a private shard maintains grades and attendance for students, public shard contains different applications that can leverage this information. For example scholarship that is given out on a regular basis based on the grades.
* Supply chain: across two private shards, passing information about components of the bigger item while maintaining proof of the components origin.

## Other

* Food ordering: three party marketplace on the blockchain, which connects restaurats, delivery and users. As food is ordered from specific resturant, delivery can pick up order on this marketplace.
* Tracking packages: the supplier posts upgrades encrypted by public key of the user, only given user can decrypt and check the status.
* Video sharing: currently many centralized services are starting to block content about blockchain. This service can store video content on IPFS or similar file storage solution and use NEAR for discovery, payments and ownership.
* Event tickets: create smart tickets which guarantees oversight, control, and communication with the fan throughout the life of the ticket. Limit ticket scalping and fraud. See https://www.artos.io/ and https://aventus.io/ 


