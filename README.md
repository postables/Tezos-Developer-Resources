# Tezos-Developer-Resources

This repository aims to serve as a collection of Tezos development resurces to assist developers in using the Tezos blockchain.

Tezos is partially built on the idea of community driven governance, and incentivization of community driven development. [Stephen Andrews](https://github.com/stephenandrews/) has done a lot of the Tezos community already and his donation address for XTZ is `tz1cLDXASgh48ntYmLqM3cqPEXmUtpJVVPma`

If you are looking for a non techincal activate your Fundraisers wallet go Stephen Andrews has a tool [activatez](https://stephenandrews.github.io/activatez/). Always DYOR (Do-Your-Own-Research) before using third party tools.

## Scripts

* `tezos_install.sh` - Installs a Tezos node
  * Tested on Ubuntu 16.04 + 18.04 although it should work with most debian distros
* `tezos_manager.sh` - Wrapper for commonly used tezos node functions
  * Tested on Ubuntu 16.04
  * Allows you to start a node, start a baker service, and other general node commands

## Resources

Various resources centered around getting a better understanding of all aspects of Tezos.

## Tezos Keys

* [decrypt encrypted private keys](https://gitlab.com/tezos/tezos/issues/254)

### Social

* [/r/tezos](https://www.reddit.com/r/tezos/)
* [Tezos matrix chat room](https://riot.im/app/#/room/#tezos:matrix.org)

### Websites

* [tezos.help](https://www.tezos.help/)
* [tezos.rocks](https://tezos.rocks/)
* [tezos.com](https://tezos.com/)

### General Information

* [Tezos - The Big Picture](http://tezos.gitlab.io/master/whitedoc/the_big_picture.html)
* [Tezos Technical FAQ](https://github.com/tezoscommunity/faq/wiki/Tezos-Technical-FAQ)

### Proof of Stake

* [liquid proof of stake](https://medium.com/tezos/liquid-proof-of-stake-aec2f7ef1da7)
* [Proof Of Stake In Tezos](http://tezos.gitlab.io/master/whitedoc/proof_of_stake.html#proof-of-stake)

### Baking

* [It's a bakers life for me](https://medium.com/tezos/its-a-baker-s-life-for-me-c214971201e1)
* [Baking Cycle Stats](https://docs.google.com/spreadsheets/d/1TkU71UPfA8g-zgy1y-wKAA3uOJCZr2LeJpjx05KUCXU/edit#gid=1225565045)
* [Baking Rights Calculator](https://bakendorse.com)
* [Baker Heatlh Charts](https://www.tezbaker.io/health/)
* [stakefish - Baking rewards calculator](https://stake.fish/calculator)
* [stakefish - Bakers Available Capacity calculator](https://tezos.fish/planner)

### Delegation

* [stakefish - Ranking based listing of Tezos Bakers and Delegation Services](https://tezos.fish/leaderboard)
* [MyTezosBaker - Listing of various delegation services](https://www.mytezosbaker.com/)
* [Whitedoc - Proof of Stake - Delegation](https://doc.tzalpha.net/whitedoc/proof_of_stake.html#delegation)

### Development
 
* [Smart Contract Tutorials](https://martin.pospech.cz/post/)
* [Getting Started With Tezos: first steps](https://martin.pospech.cz/post/getting_started_with_tezos/)
* [Developer Documentation](https://doc.tzalpha.net/index.html)

## Smart Contract Languages

* [The Michelson Language](https://www.michelson-lang.com/)
* [Liquidity](https://www.liquidity-lang.org/)
* [fi](https://github.com/stephenandrews/fi)
* [Juvix PoC, possibly no updates in future](https://github.com/cwgoes/juvix)

### Michelson

* [language specification - Table Of Contents](https://doc.tzalpha.net/whitedoc/michelson.html#table-of-contents)

#### Michelson Tutorials

* [contract a day](https://www.michelson-lang.com/contract-a-day.html#sec-1)
* [Optimizing Stack manipulation in Michelson](https://hackernoon.com/optimizing-stack-manipulation-in-michelson-31ba7ff11a3a)

### Liquidity

* [Documentation](https://github.com/OCamlPro/liquidity/blob/master/docs/liquidity.md)
* [Try Liquidity - Online Compiler and Development Environment](http://www.liquidity-lang.org/edit/)

#### Liquidity Tutorials

* [Getting started with Liquidity: coinflip](https://martin.pospech.cz/post/getting_started_with_liquidity/)
* [Getting started with Liquidity: authentication](https://martin.pospech.cz/post/getting_started_with_liquidity_2/)

#### Examples

Examples cover basic hello world, crowd funding, and a mini dapp called King Of The Tezos

##### Advanced Liquidity Examples

* `Examples/KingOfTheTezos/KingOfTheTezos_V4.ml` - Tezos version of King Of The Ether.
* [identity](https://gist.github.com/et4te/4dea46b77c001423d6b9a6e275ab67f6)

##### Basic Liquidity Examples

* `Examples/hello_world.ml` is a basic hello world in liquidity
* `Examples/string_set.ml` is a basic liquidity contract, allowing one to set a string value in storage
* `Examples/string_set_with_cost.ml` allows you to set a string in storage if you pay 10tz
* `Examples/multi_string_set.ml` allows you to set two strings in storage
* `Examples/multi_string_set_with_cost.ml` allows you to set two strings in storage, and the value of the transaction if you pay 10tz or more
* `Examples/Crowdfund/Basic.sol` - Extremely basic crowdfunding example

## Tezos Dapps

* [Luckytz, the first public Tezos dapp](https://luckytez.github.io/)

## Tools

### Block Explorers

* [ostez - possibly broken](http://ostez.com/)
* [tzscan.io](https://tzscan.io/)
* [tezos.id](https://tezos.id/)

### Golang

* [goTezos](https://github.com/DefinitelyNotAGoat/goTezos)
* [Golang RPC API - WIP](https://github.com/postables/TGo)

### Javascript

* [ezts](https://github.com/stephenandrews/eztz)

## Other Donation Addresses

* [Postables](https://github.com/postables) `tz1Wpefz7KdEkVf2hXGMRKYymVjML9Zpi1r7`
* [DefinitelyNotAGoat](https://github.com/DefinitelyNotAGoat/goTezos) `tz1hyaA2mLUQLqQo3TVk6cQHXDc7xoKcBSbN`
