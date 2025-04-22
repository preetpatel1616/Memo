# 🧠 Memo – ETHGlobal Hackathon Submission

**Memo** is a blockchain-based platform built during the ETHGlobal SpaceWarp Hackathon. It enables digital creators to securely publish projects, monetize via token sales, and control access to their content using token-gated permissions.

## 🔗 Live Showcase
[View Memo on ETHGlobal](https://ethglobal.com/showcase/memo-70uua)

## ✨ Features

- 🔐 **Token-Gated Access** – Viewers can only access content after verifying token ownership.
- 🎨 **Creator Upload Flow** – Creators can mint tokens and upload gated digital projects.
- 🛒 **Token Sale Setup** – Creators can configure supply and pricing for each upload.
- 🌐 **Explore Page** – Users can browse and discover public projects.
- 🧾 **Creator Dashboard** – See listed content and access stats in a centralized panel.

## 🧱 Tech Stack

| Component       | Technology                          |
|----------------|--------------------------------------|
| Frontend        | React.js, Tailwind CSS              |
| Smart Contracts | Solidity (ERC-1155)                 |
| Blockchain      | Polygon Mumbai Testnet              |
| Wallet Auth     | Metamask, WalletConnect             |
| Tooling         | Hardhat                             |

## 🏗️ Architecture & Design

Memo is composed of two main layers:

- **Frontend App:** Built in React, offering creators an intuitive UI to list content and manage tokens.
- **Smart Contracts:** Handle minting, ownership verification, and access control using ERC-1155 tokens.

> We chose ERC-1155 for its flexibility in minting multiple token types with fewer transactions.

## 🤝 Team Collaboration

This project was developed during our internship at **Kyoorius Communications** as part of ETHGlobal’s hackathon. When a teammate suggested adding extended features mid-hackathon (explore page, creator dashboard, and royalty systems), I facilitated a focused discussion to prioritize essential functionalities and proposed building extra features in parallel. This approach helped us deliver a complete MVP and still include enhancements.

## ✅ Achievements

- Completed core features for secure content upload, token sales, and access control
- Successfully implemented both the project exploration page and creator dashboard
- Delivered a fully functional prototype within the 3-day hackathon window

## 🧠 Lessons Learned

- Prioritization is key in time-constrained environments
- Open communication can resolve conflicting team priorities
- Gained experience integrating ERC-1155 with Web3 UI workflows

## 🚀 Future Enhancements

- Implement automated royalty distribution
- Add detailed analytics for creators
- Integrate decentralized storage for large files

## 📂 Repository Structure

/contracts # Solidity smart contracts /src # React frontend /components # UI components /pages # App pages /utils # Wallet and contract interaction logic


## 📎 Resources

- [GitHub Repo](https://github.com/preetpatel1616/Memo)
- [ETHGlobal Showcase](https://ethglobal.com/showcase/memo-70uua)

---

> **Note:** This was a hackathon prototype deployed on the Polygon Mumbai testnet. It is not intended for production use.

