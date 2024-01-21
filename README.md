# PoSFacilitator (PoSMinter)

## Proof of Stake minter facilitates borrowing GHO token on L2 based on the ETH supplied to Aave protocol on Ethereum network with help of Chianlink CCIP.

Proof of Stake facilitator (or PoSMinter) enables users to borrow GHO token on L2 based on collateralized ETH on Ethereum network. The collateralized ETH will be agreed to be swapped as rETH to secure the Ethereum network and to get rewards from it. 

Chainlink CCIP will be the messenger between two smart contract on different blockchains to check the collateral(ETH) on L1 and the repayment of GHO on L2.

The problems that PoSMinter solves:
Collaterizing ETH on L1 and borrowing GHO token on L2 provide benefits on taxation, unnecessary bridge fee, cheaper gas fee of L2 and security of ETH on L1.

## Technologies
From a technical perspective, PoSFacilitator is composed of a couple of smart contracts that enables the minting of GHO using `GhoFacilitator` and messaging between blockchains with Chainlink CCIP in order to check the collateral and the repayment.
