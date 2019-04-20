# Solidity Development

A few different contracts developed in different stages to learn about the Solidity programming language. These contracts are a part of a final year honour's project for a dissertation concerning Ethereum blockchain technologies and their use as an immutable record store for student certificates and achievements.

## Contracts
The smart contracts within this repository written in Solidity show the different stages of contract evolution and experimentation with language. The overall goal of the project using these contracts, was to develop a basic prototype Ethereum application that could store and manage student records. The application was meant to operate as a university or organization deploying one contract to control the addition, modification, or deletion of records added to it, and a secondary contract to act as the student or member wanting access their record and their certificate gained from the university or organization. The contracts were developed in the Remix IDE and deployed through it as well. The goal was not in itself to create a fully developed DApp, but to only demonstrate that the logic behind storing and retrieving of data could be done with Ethereum smart contracts. Therefore, no interface was developed for the application, and all interactions with the contracts was done through the Remix IDE. 

## Records
The two records files were created to contain the variables needed to be stored and used in the contract, structured in the exact order the contract methods required to either create a student record, or award record. This was for ease of copying details over quickly to create records. The **example_records.txt** file was used for development in the Remix IDE while using a JavaScript VM and testing the contract and methods. The **rinkby_records.txt** was the records that would be tested when the contract deployed to the Rinkby testnet using a set of accounts generated from a Metamask account, used for development purposes only. 