---
sidebar_position: 1
---
# Treasury
Treasury actions are actions a DAO can decide to run, specifically involving tokens being used from the DAO's treasury.

## Spend 
*Spend native or CW20 tokens from the treasury.*
## Manage Staking 
*Manage native token staking: claim rewards, delegate, redelegate, and undelegate.*
## Manage Treasury Tokens 
*Manage Tokens displayed on your DAO's treasury page.*
## Token Swap 
*Token swap is an escrow contract for swapping between native and cw20 tokens.*

### Examples Involving Token Swap

- **DAO collaborations** - Two or more DAOs are able to make use of the token swap contract serving as the escrow during any agreements involving the exchange of funds between the DAOs.
- **DAO onboarding** - DAO onboarding can be powered by requiring an initial deposit in exchange for the DAO's ownership token.
- **Custom escrow logic** - The token swap contract can be customized with further expectations to fulfill an exchange of funds.

### Token Swap Workflow
The contract is instantiated with two counterparties and their promised funds. Promised funds may either be native tokens or cw20 tokens. Upon both counterparties providing the promised funds the transaction is completed and both sides receive their tokens. At any time before the other counterparty has provided funds a counterparty may withdraw their funds.

#### Withdrawing a Token Swap 
*Withdraw funds from a token swap that has not yet completed.*

## Enable Vesting Payments 
*Configure vesting payments and enable them on one or more chains.*

## Community Pool Deposit
*Deposit funds into the community pool.*