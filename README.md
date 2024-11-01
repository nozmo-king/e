# e

---

## Overview

**e** is an innovative Proof-of-Work web-currency project designed to redefine digital currency by introducing novel concepts like dual-layer PoW, mini-PoW puzzles, and a flexible block size that doubles with every reward halving. This project aims to create a decentralized ecosystem that includes an encrypted marketplace, P2P poker, and a web of trust. "e" is optimized for scalability and user engagement, supporting advanced features such as encrypted Paymail and IRC-like messaging.

### Key Features
- **Dual-layer Proof-of-Work**: SHA-512 for primary blockchain mining, SHA-256 for mini-PoW (e182).
- **Scalable Block Size**: Initial 25 MB blocks, doubling at each block reward halving.
- **Mini-PoW Driven Marketplace**: Gamified marketplace and P2P games (like poker) secured through mini-PoW challenges.
- **Encrypted Messaging and Paymail**: Secure, private email and messaging with Paymail integration.
- **Economics and Incentives**: Innovative reward structure with a larger supply than Bitcoin and unspent UTXO donations at each halving.

---

## Getting Started

### Prerequisites
- **C Compiler** (e.g., `gcc`)
- **OpenSSL**: Required for SHA-512 and SHA-256 cryptographic functions. Install it on Unix-based systems with:
  ```bash
  sudo apt-get install libssl-dev
  ```
- **Git**: To clone the repository and collaborate.

### Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/YOUR_USERNAME/e_blockchain.git
   cd e_blockchain
   ```

2. **Compile the Project**:
   Run `make` to compile the project:
   ```bash
   make
   ```

3. **Run the Program**:
   After building, you can run the program with:
   ```bash
   ./e_blockchain
   ```

### Project Structure
```
e_blockchain/
├── docs/                   # Documentation and whitepaper
├── src/                    # Source code files
│   ├── main.c              # Main blockchain program
│   ├── block.c             # Core blockchain blocks
│   ├── transaction.c       # Transaction handling
│   ├── pow.c               # Proof-of-Work algorithms
│   └── utils.c             # Utility functions
├── tests/                  # Unit tests and integration tests
├── data/                   # Data files (e.g., blockchain and wallets)
├── README.md               # Project overview and instructions
└── Makefile                # Build file for compiling the project
```

---

## Usage

After setting up the project, here’s how you can interact with "e":

- **Mining Blocks**: Run the primary PoW process (SHA-512) to mine new blocks.
- **Completing Mini-PoW Puzzles**: Engage in e182 puzzles to access the marketplace, messaging, and games.
- **Sending Transactions**: Send transactions through the main blockchain, secured via both PoW layers.
- **Messaging**: Encrypted messaging via Paymail (under development).

---

## Development

### Contributing

1. **Fork the Repository**
2. **Create a Feature Branch**: 
   ```bash
   git checkout -b feature/new-feature
   ```
3. **Commit Changes**:
   ```bash
   git commit -m "Add new feature"
   ```
4. **Push to Branch**:
   ```bash
   git push origin feature/new-feature
   ```
5. **Open a Pull Request**

### Testing

Testing is key to ensuring the security and reliability of "e." Unit tests and integration tests will be maintained in the `/tests/` directory. Run all tests with:
```bash
make test
```

---

## Future Roadmap

- **Complete e182 Mini-PoW System**: Full implementation of the dual PoW layer.
- **P2P Poker and Marketplace**: Secure gaming environment and marketplace within the blockchain.
- **Encrypted Messaging**: Implement Paymail integration and secure communication.
- **Block Size Management**: Automatic scaling of block size with each halving event.

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Let me know if you'd like to adjust or expand any section, and feel free to replace `"YOUR_USERNAME"` in the GitHub URL with your GitHub username!
