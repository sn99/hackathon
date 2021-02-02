# Hackathon

[![Build Status](https://www.travis-ci.com/sn99/hackathon.svg?branch=master)](https://www.travis-ci.com/sn99/hackathon)

------------------------------------------------------------------------------------------------------------------------

## What is blockchain

Decentralized Applications (or DApps) are applications that do not rely on a centralized backend running in AWS or Azure
that power traditional web and mobile applications (outside of hosting the frontend code itself). Instead, the 
application interacts directly with a blockchain which can be thought of distributed cluster of nodes analogous to 
applications interacting directly with a “masterless” cluster of Cassandra nodes with full replication on every peer 
in an untrusted peer-to-peer network.

DApps are the frontend apps which interact with these blockchains over an API. For Ethereum, this API is a JSON-RPC layer
called the Ethereum Web3 API which Moesif supports natively.

## What is Ethereum?

Ethereum is an implementation of blockchain technology that can run smart contracts. The Ethereum virtual machine is 
Turing complete and can run arbitrary computation directly on the blockchain network. Whereas Bitcoin has a limited set 
of commands, an Ethereum contract allows an application developer to specify exactly what transactions can be performed 
on a contract. Simple smart contracts can be thought of as a Finite State Machine (FSM) with a set of custom transitions.

## What is Smart Contracts?

Smart contracts can enable a blockchain user exchange money and property or perform other actions among a group of 
users such as voting without any central authority.

## What is JSON-RPC

JSON-RPC is a stateless, light-weight remote procedure call (RPC) protocol using JSON for a payload. Unlike RESTful APIs 
which are resource-centric, RPC APIs like JSON-RPC are procedural and can be more tightly coupled than RESTful APIs.

Frontend apps communicate with the Ethereum cluster using JSON-RPC. Web3 is the Ethereum compatible API and bindings 
which is built using the JSON-RPC spec.

Any decentralized app must use a Web3 SDK such as Web3.js for a browser based DApps.

------------------------------------------------------------------------------------------------------------------------

## License

Licensed under either of these:

 * Apache License, Version 2.0, ([LICENSE-APACHE](LICENSE-APACHE) or
   https://www.apache.org/licenses/LICENSE-2.0)
 * MIT license ([LICENSE-MIT](LICENSE-MIT) or
   https://opensource.org/licenses/MIT)
