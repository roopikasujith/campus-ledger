# Campus Ledger 🎓⛓️

### A Blockchain-Based Platform for Campus Events and Token Rewards

Campus Ledger is a web platform that manages student activities, event participation and rewards using blockchain technology. Students book event tickets with digital tokens (**CTK**) through their MetaMask wallet, and administrators (club organizers) create events and distribute tokens as rewards. Transactions are processed through smart contracts on the Ethereum Sepolia testnet, so records are transparent and tamper-proof.

The application is deployed on PythonAnywhere.

---

## ❗ Problem

Traditional campus systems rely on manual, centralized processes. This leads to a lack of transparency, insecure records, and no reliable way to track and reward student participation.

## 🎯 Objectives

- Build a secure, easy-to-use web platform for students and administrators
- Use smart contracts and tokens for transparent, tamper-proof records of participation and transactions
- Provide verifiable activity tracking, including event history and token rewards
- Support secure authentication, wallet integration and real-time monitoring

---

## ✨ Features

### 👩‍🎓 Student Portal
- Sign up and log in with username, password and MetaMask wallet address
- Dashboard showing token balance, total earned, total spent, clubs and recent transactions
- Browse upcoming events with club, date, time and token cost
- Book event tickets using CTK tokens
- Profile page with wallet address, QR code and full transaction history

### 🛠️ Admin Portal (Club Organizers)
- Separate admin login and dashboard
- Add events with token cost
- Send (issue) tokens to students as rewards
- Master ledger showing total distributed, total received and treasury balance

### ⛓️ Blockchain
- Smart contracts written in Solidity automate bookings and reward distribution
- Transactions recorded on the Ethereum Sepolia testnet
- Wallet signing through MetaMask using the Ethers.js library

---

## 🛠️ Tech Stack

| Area | Technologies |
|------|--------------|
| Frontend | HTML, CSS, JavaScript |
| Backend | Python, Flask |
| Blockchain | Ethereum Sepolia Testnet, Solidity, Ethers.js |
| Wallet | MetaMask |
| Database | SQLite |
| Tools | Git, Visual Studio Code, PythonAnywhere |

---

## 🔄 How It Works

1. Users register as a **student** or **administrator** and log in.
2. Administrators add events and set the token cost.
3. Students explore events on their dashboard and book tickets with CTK tokens.
4. Bookings and reward transfers run through smart contracts and are recorded on the blockchain.
5. Students and administrators view participation history, token transactions and rewards on their dashboards.

---

## 🗄️ Database

SQLite stores users, events, tokens, rewards and transactions (off-chain data). Blockchain transaction records are stored on the Sepolia testnet.

---

## 🚀 Setup

1. Download or clone this repository.
2. Install the Python packages the project needs (Flask and the other libraries used in the code).
3. Install the MetaMask browser extension and switch it to the **Sepolia** test network.
4. Get free Sepolia test ETH to pay for transaction fees.
5. Start the Flask application and open it in your browser.

> 🔒 Never share your MetaMask private key or seed phrase. Keep all secrets out of the repository.

---

## 📸 Screenshots

Screenshots of the home page, student dashboard, ticket booking, student profile, admin dashboard and token transfer can be added here.

---

## 🔮 Future Scope

- Optimize smart contracts for faster, lower-cost transactions
- Mobile app version
- Analytics for participation and engagement trends
- Inter-college platform for multiple institutions
- QR or NFC based attendance with automatic reward distribution

---

## 👩‍💻 Team

B.Tech Computer Science and Engineering, SCMS School of Engineering and Technology (APJ Abdul Kalam Technological University), March 2026

- Roopika Sujith
- Rushdha Mariyam M
- Sandra Subramanian
- Shana Thayyil

**Project Guide:** Ms. Anisha V Lal, Assistant Professor, Department of Computer Science and Engineering
