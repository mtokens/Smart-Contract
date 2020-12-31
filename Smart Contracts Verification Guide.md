Smart Contracts Verification Guide
===
M-Tokens smart contract codes have been audited by a third-party, and available here: [PeckShield Audit Report](https://www.mtokens.network/PeckShield-Audit-Report-M-Tokens.pdf)

To verify that on-chain M-Tokens are consistent with the smart contracts audited, there are 2 primary steps:
 
STEP 1: Verify that the smart contract codes on the GitHub code repository are of the same version as the codes audited
---
M-Tokens smart contract GitHub repository: https://GitHub.com/mtokens. Commit ID is `5c490c2`. 

The subject audited in the [PeckShield Audit Report](https://www.mtokens.network/PeckShield-Audit-Report-M-Tokens.pdf) also targets commit ID `5c490c2`.

It can be confirmed that the two are of the same version upon taking the steps above.
 
STEP 2: Verify that the on-chain contracts are consistent with the smart contract codes on the GitHub repository
---
It can be done through etherscan.io:

AAA.sol on-chain contract code address: https://etherscan.io/address/0xffffffff#code. The corresponding contract code within the GitHub repository:https://GitHub.com/mtokens (to be provided) 

BBB.sol on-chain contract address: https://etherscan.io/address/0xffffffff#code. The corresponding contract code within the GitHub repository:https://GitHub.com/mtokens (to be provided) 