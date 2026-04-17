# WalletX 

WalletX is  wallet dashboard built using **Next.js**, **Wagmi**, **Tailwind** , **framer motion** and **RainbowKit**.


**Website URL**

https://brilliant-llama-42c0bf.netlify.app/


## Features

- Connect wallet using RainbowKit
- Supports injected wallets 
-  Disconnect functionality
-  Displays ETH balance & Converts ETH → USD (static rate)
- Send ETH to any valid address & Displays transaction hash after success
- Generates QR code for wallet address
- Stores transaction history locally (via localStorage)
- Set daily spending limit (UI only)
- Can Clear transaction history & Clear all stored data


---

###  UI/UX

* Animated transitions using Framer Motion
* Glassmorphism design
* Responsive layout with sidebar navigation

---

## 🛠️ Tech Stack

* **Frontend Framework:** Next.js (App Router)
* **Web3 Integration:** Wagmi + Viem
* **Wallet UI:** RainbowKit
* **Styling:** Tailwind CSS
* **Animations:** Framer Motion
* **QR Code:** qrcode.react

---

## 📁 Project Structure

```
frontend/
├── app/
│   ├── page.tsx        # Main wallet dashboard
│   ├── globals.css     # Global styles (Tailwind)
├── components/         
├── public/             # Images (logo, backgrounds)
├── package.json
```

--- 



