# @eth-optimism/contracts-periphery

## 0.2.4

### Patch Changes

- 7215f4ce: Bump ethers to 5.7.0 globally
- 0ceff8b8: Drippie Spearbit audit fix for issues #32 and #33, clarify behavior of executable function
- 0ceff8b8: Drippie Spearbit audit fix for issue #25, reorder DripStatus enum for clarity
- 0ceff8b8: Drippie Spearbit audit fix for issue #44, document drip count and increment before external calls
- 0ceff8b8: Drippie Spearbit audit fix for issue 24, use call over transfer for withdrawETH
- 0ceff8b8: Drippie Spearbit audit fix for issue 22, remove unnecessary gas parameter
- 0ceff8b8: Drippie Spearbit audit fix for issue #34, missing natspec
- 0ceff8b8: Drippie Spearbit audit fix for issue #28, document dripcheck behavior in drip function
- 0ceff8b8: Drippie Spearbit audit fix #42, remove unnecessary SLOADs in the status function
- 0ceff8b8: Drippie Spearbit audit fix for issue #39, update to latest version of Solidity
- 0ceff8b8: Drippie Spearbit audit fix for issue #21, use correct version of Solmate
- 0ceff8b8: Drippie Spearbit audit fix for issue #31, require explicit opt-in for reentrant drips
- 0ceff8b8: Drippie Spearbit audit fix for issue #45, calldata over memory to save gas
- 0ceff8b8: Drippie Spearbit audit fix for issue #35, correct contract layout ordering

## 0.2.3

### Patch Changes

- f4bf4f52: Fixes import paths in the contracts-periphery package

## 0.2.2

### Patch Changes

- ea371af2: Support deploy via Ledger or private key

## 0.2.1

### Patch Changes

- 93d3bd41: Update compiler version to 0.8.15
- bcfd1edc: Add compiler 0.8.15
- 0bf3b9b4: Update forge-std

## 0.2.0

### Minor Changes

- 8a335b7b: Fixes a bug in the OptimismMintableERC721. Requires an interface change, so this is a minor and not patch.

### Patch Changes

- 95fc3fbf: Add typechain with ethers v5 support
- 019657db: Add TeleportrDeposit and TeleportrDisburser to contracts-periphery
- 6ff5c0a3: Cleaned up natspec for Drippie and its dependencies
- 119f0e97: Moves TeleportrWithdrawer to L1 contracts folder
- 9c8b1f00: Bump forge-std to 62caef29b0f87a2c6aaaf634b2ca4c09b6867c92
- 89d01f2e: Update dev deps

## 0.1.5

### Patch Changes

- 3799bb6f: Deploy Drippie to mainnet

## 0.1.4

### Patch Changes

- 9aa8049c: Deploy NFT bridge contracts

## 0.1.3

### Patch Changes

- da1633a3: ERC721 bridge from Eth Mainnet to Optimism
- 61a30273: Simplify, cleanup, and standardize ERC721 bridge contracts.
- a320e744: Updates contracts-periphery to use the standardized hardhat deploy config plugin
- 29ff7462: Revert es target back to 2017
- 604dd315: Deploy Drippie to kovan and OP kovan

## 0.1.2

### Patch Changes

- e0b89fcd: Re-deploy RetroReceiver
- 982cb980: Tweaks Drippie contract for client-side ease
- 9142adc4: Adds new TeleportrWithdrawer contract for withdrawing from Teleportr

## 0.1.1

### Patch Changes

- 416d2e60: Introduce the Drippie peripheral contract for managing ETH drips

## 0.1.0

### Minor Changes

- f7d964d7: Releases the first version of the contracts-periphery package

### Patch Changes

- d18ae135: Updates all ethers versions in response to BN.js bug
- Updated dependencies [d18ae135]
  - @eth-optimism/core-utils@0.8.5
