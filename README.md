<h1 align="center">
  <br>
   <img width="200" src="https://raw.githubusercontent.com/solana-labs/token-list/main/assets/mainnet/StepAscQoEioFxxWGnh2sLBDFp9d8rvKz2Yp39iDpyT/logo.png" alt="step logo"/>
  <br>
</h1>

# Token List Overrides

## What is this?

An extension of Solana Labs [token-list]( https://github.com/solana-labs/token-list ) repo for faster support of tokens

Token list is an authoratative list of metadata for SPL tokens, which do not come embedded with much data of their own

To solve this, token-list allows for a centralized place to add natural token metadata attributes like symbol, name, icon

The Solana Labs token-list can be a mess, and sometimes we need to circumvent it in order to support a token with quick turn-around

## Connection

This token-list-overrides repo is pulled in by the API. The API seeks to pull in updates about every 3 hours

Tokens defined here will override or be added to the Solana Labs token-list

The API can be restarted to immediately pull in new `token-list-overrides` changes immediately
