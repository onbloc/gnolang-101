# GNOLANG 101

## Contents 
- [Introduction](##Introduction)
- [Resources](##Resources)
- [Course](##Course)
- [Community](##Community)
- [Contribute](##Contribute)

## Introduction

Welcome to GNOLANG 101!

This course is designed for aspiring programmers who are looking to become a smart contract developer on Gnoland, a scalable layer 1 with built-in concurrency.

Existing smart contract platforms are struggling with mass adoption due to technical issues such as 1) low throughput, 2) non-interoperability, or 3) flawed tokenomics.

Gnoland addresses these problems with the highly performant Tendermint Consensus algorithm and Gnolang, a fork of Golang. This course focuses on Gnolang, the language that is used in the core modules of Gnoland and its dapps. Highlights of Gnolang as described in its official docs are as follows:

 - Like interpreted Go, but more ambitious.
 - Completely deterministic, for complete accountability.
 - Transactional persistence across data realms.
 - Designed for concurrent blockchain smart contracts systems. 

Gnolang is in its early stage, and therefore we're in need of passionate developers that can help us build the tools, applications, and modules to create a vibrant ecosystem centered around quality software.

This course consists of resources, tutorials, and guides that will help you get started on your journey as a Gnolang developer. By the end of the course, you will understand how to write and publish contracts on the Gnoland blockchain in Gnolang. If you ever run into any issues, reach out for help on [the Discord server](https://discord.com/invite/3YbdqVP8Tb) where we have active developers willing to support newcomers!

**This course assumes that you have a moderate degree of programming skills.*

## Resources
A full list of resources that you will need to access throughout the course.

### Reading
- [Readme](https://github.com/gnolang/gno#readme)
- [Philosophy](https://github.com/gnolang/gno/blob/master/PHILOSOPHY.md)
- [Plan](https://github.com/gnolang/gno/blob/master/PLAN.md)
- [Roadmap](https://github.com/gnolang/gno/blob/master/PLAN.md)

### Repositories
- [gno](https://github.com/gnolang/gno)
- [awesome-gno](https://github.com/gnolang/awesome-gno)
- [www.gno.land](https://github.com/gnolang/www.gno.land)
- [tendermint](https://github.com/gnolang/tendermint)
- [bounties](https://github.com/gnolang/bounties)
- [gno-basics](https://github.com/moul/gno-basics)
- [adena-extension](https://github.com/onbloc/adena-extension)

### Tutorials
- [The Official Golang Tutorial](https://go.dev/doc/tutorial/)
- [The Gnoland Quickstart Guide](https://test2.gno.land/r/boards:testboard/5)
- [Gno Basics](https://github.com/moul/gno-basics)

### Tools
- [Adena](https://adena.app/)
- [Gnotools](https://app.gno.tools/r/boards:testboard)
- [Gnoscan](https://gnoscan.io)

## Course
Read the instructions and follow the checklist in order.

### Instructions
-  `read`: Items to be read, be they journals, write-ups, or even lines of code.
-  `do`: Items that require you to perform specific tasks. These items usually include writing and running your own code.
- Clone this repo and check off items to track your progress!

### Checklist

1. - [ ] `read` [the README file](https://github.com/gnolang/gno#readme)
2.  - [ ] `read` [the Philosophy](https://github.com/gnolang/gno/blob/master/PHILOSOPHY.md)
3.  - [ ] `read` [the Plan](https://github.com/gnolang/gno/blob/master/PLAN.md)
4.  - [ ] `read` [the Roadmap](https://github.com/gnolang/gno/blob/master/ROADMAP.md)
5. - [ ] `do` [Join the Discord Server](https://discord.gg/3YbdqVP8Tb)
6.  - [ ] `do` [the Official Golang Tutorial](https://go.dev/doc/tutorial/) (skip if you know Golang)
7.  - [ ] `do` [Build](https://github.com/gnolang/gno/blob/master/examples/gno.land/r/boards/README.md#build-gnokey-create-your-account-and-interact-with-gno) `gnokey` [and create an account](https://github.com/gnolang/gno/blob/master/examples/gno.land/r/boards/README.md#build-gnokey-create-your-account-and-interact-with-gno)
8.  - [ ] `do` [Acquire testnet tokens from the faucet](https://test2.gno.land/faucet)
9.  - [ ] `do` [Create a board, a post, and a comment on test2.gno.land](https://test2.gno.land/r/boards?help)
10. - [ ] `do` [Set up a local node](https://github.com/gnolang/gno/blob/master/examples/gno.land/r/boards/README.md#starting-a-local-gnoland-node)
11. - [ ] `do` [Publish sample packages](https://github.com/gnolang/gno/blob/master/examples/gno.land/r/boards/README.md#publish-the-gnolandpavl-package)
12. - [ ] `do` [gno-basics 001-hello](https://github.com/moul/gno-basics/tree/main/001-hello)
13. - [ ] `do` [gno-basics 002-args](https://github.com/moul/gno-basics/tree/main/002-args)
14. - [ ] `do` [gno-basics 003-data](https://github.com/moul/gno-basics/tree/main/003-data)
15. - [ ] `do` [gno-basics 004-render](https://github.com/moul/gno-basics/tree/main/004-render)
16. - [ ] `read` [package](https://github.com/gnolang/gno/tree/master/examples/gno.land/p/avl) `avl`
17. - [ ] `read` [package](https://github.com/gnolang/gno/tree/master/examples/gno.land/p/dom) `dom`
18. - [ ] `do` [gno-basics 005-import](https://github.com/moul/gno-basics/tree/main/005-import)
19.  - [ ] `read` [package]((https://github.com/gnolang/gno/tree/master/examples/gno.land/p/grc/grc20)) `grc20`
20. - [ ] `do` [gno-basics 006-grc20](https://github.com/moul/gno-basics/tree/main/006-grc20)
21. - [ ] `read` [package](https://github.com/gnolang/gno/tree/master/examples/gno.land/p/grc/exts/vault) `vault`
22. - [ ] `do` [gno-basics 007-vault](https://github.com/moul/gno-basics/tree/main/007-vault)
23. - [ ] `do` [explore more packages](https://github.com/gnolang/gno/tree/master/examples/gno.land/p)
24. - [ ] `do` [explore more realms](https://github.com/gnolang/gno/tree/master/examples/gno.land/r)
25. - [ ] `do` [explore bounty programs](https://github.com/gnolang/bounties)
26. - [ ] `do` [Write & publish your own packages & realms](https://test2.gno.land/)

## Community
- [Discord](https://discord.gg/3YbdqVP8Tb)
- [Telegram](https://t.me/gnoland)
- [Twitter](https://twitter.com/_gnoland)
- [Gnoland Boards](https://gno.land/r/boards)

## Contribute
Gnolang is a new language with new updates being shipped almost every day. We'll try to keep this course as up-to-date as possible, but we'd appreciate your help to cover as much information as possible. 

Please take a look at the [contribution guidelines](https://github.com/onbloc/gnolang-101/contribution-guidelines.md) and become a TA by helping us develop this course!
