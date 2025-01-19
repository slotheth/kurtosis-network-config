# Network Configuration for Participants

This configuration file defines the setup and parameters for participants in the network, including Execution Layer (EL), Consensus Layer (CL), Validator Client (VC), and other services. It provides a detailed structure to customize the network behavior for devnet and other testnet environments.

## File Overview

### Participants Configuration
	- Execution Layer (EL):
	- Specify EL type (e.g., geth, nethermind).
	- Customize EL image, log levels, environment variables, and resource allocations.
	- Consensus Layer (CL):
	- Specify CL type (e.g., lighthouse, prysm).
	- Configure image, logging, resource requirements, and optional supernode flag.
	- Validator Client (VC):
	- Define the validator type, image, and resource allocations.

### Network Parameters
	- General Settings:
	- Network name (kurtosis by default).
	- Chain ID (3151908 for Kurtosis).
	- Staking contract address.
	- Slot and validator key configurations.
	- Genesis Settings:
	- Configure delay, gas limit, and churn limits.