# [Openlinks.io](https://openlinks.io)

[![made-with-javascript](https://img.shields.io/badge/Made%20with-JavaScript-1f425f.svg)](https://www.javascript.com)
[![](https://img.shields.io/badge/project-IPFS-blue.svg?style=flat-square)](https://ipfs.io/)

### Using Web3.Storage and IPFS, easily create a personalized Link in Bio webpage with user defined links.

- Login to the app and withn a few clicks create your own personalized link in bio website on IPFS
- Change the website anytime (user's website link is updated with a new one)

### [Live Openlinks Page Example](https://bafybeihwda3qc4ck4txip3aj2kqvnshp22c5qz3ewoxuberskcb64ckr5m.ipfs.dweb.link/Logan-L.html)

<img width="695" alt="Screen Shot 2022-10-17 at 11 17 50 PM" src="https://user-images.githubusercontent.com/30084404/196334418-2865c68e-fd5c-498f-a1b3-43a8f82a6115.png">

## User Flow
- [User signs in with an email address (SSO) at Openlinks.io](https://openlinks.io) 
- User inputs their links, a title for each link, a profile photo, & gives the webpage a title
- Web-page & profile photo are exported to IPFS (web3.storage)
- User is returned an IPFS webpage address (a CID and link)
- Using various IPFS Gateways, users can access webpages from anywhere

## Development Configuration
This code is a full functioning front-end. If you want to edit this yourself, you will need to create an auth0 account and follow the instructions below-

## Recently Completed 
- responsive homepage- mobile optimized (less borked)
- themes backend/Added another Lambda function for themes that exports page to an S3 bucket before upload
- privacy policy

## Currently Working on 
- Adding homepage 
- Seperation of domains
- Adding Themes & webpage preview to front-end
- update IPFS website name with IPNS links via Web3.Name
