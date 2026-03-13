# Algorand Lottery

A decentralized lottery smart contract built with PyTeal and deployed on the Algorand blockchain.

## Overview

A simple lottery contract where participants can enter by sending ALGO, and a winner is selected to claim the prize pool. Built using PyTeal — a Python library for writing Algorand smart contracts.

## Features

- **Enter Lottery** — Users pay an entry fee to participate
- **Random Selection** — Winner selection through on-chain randomness
- **Prize Pool** — Accumulated entry fees distributed to the winner
- **On-chain Logic** — Fully decentralized execution on Algorand

## Tech Stack

- **PyTeal** — Python library for Algorand smart contracts
- **Algorand** — Layer 1 blockchain
- **Python** 3.x

## Getting Started

### Prerequisites

- Python 3.x
- PyTeal (`pip install pyteal`)
- Algorand SDK (`pip install py-algorand-sdk`)

### Installation

```bash
git clone https://github.com/okekefrancis112/algorandLottery.git
cd algorandLottery
pip install pyteal py-algorand-sdk
```

### Compile Contract

```bash
python lottery_contract.py
```

## Project Structure

```
├── lottery_contract.py     # PyTeal lottery smart contract
└── README.md
```

## License

MIT
