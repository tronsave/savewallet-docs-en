# FAQs

### Why do some transactions have a "delegate energy" transaction right after them?

**First, what are Energy and Bandwidth on TRON?**

Energy and Bandwidth are TRON's resource system for processing transactions and running smart contracts.

* **Energy** powers smart‑contract execution (for example, TRC‑20 transfers like USDT). It can be obtained by staking TRX, but there's **no free daily Energy** allowance.
* **Bandwidth** is used for ordinary operations such as TRX transfers, staking, and unstaking. Each account gets **600 free Bandwidth** per day.

**SaveWallet's fee‑saving mechanism:**

When you make a transaction, SaveWallet checks how much Energy your wallet has. If there isn't enough, it automatically **rents** the Energy it needs from the **Tronsave** marketplace. Paying the fee with rented Energy can be **up to ~80% cheaper** than burning TRX directly.

That's why you'll sometimes see an additional **delegate‑energy** transaction alongside your transfer — it's the Energy being delegated to your account so your transaction settles cheaply. Renting from Tronsave is safe and reliable (Tronsave is verified by the TRON community and has won multiple hackathon awards).

### Is SaveWallet custodial? Can the team access my funds?

No. SaveWallet is **fully self‑custodial**. Your recovery phrase and private keys are generated and stored only on your device. No one — including the SaveWallet team — can access or move your funds.

### What happens if I lose or change my phone?

Your wallet lives on the blockchain, not on the device. Install SaveWallet on the new device and **import** your wallet using your recovery phrase or private key. This is why backing up your recovery phrase is essential — if you lose it and your device, the wallet cannot be recovered.

### Why are SaveWallet's fees lower than other wallets?

Because SaveWallet automatically optimizes Energy for every transaction, renting it from the Tronsave marketplace instead of burning TRX. For frequent transfers, setting up a [Resource Account](../mobile-app/savings-discover.md) makes fees even lower.

### Which network and tokens does SaveWallet support?

SaveWallet runs on **TRON**. It supports **TRX**, **USDT (TRC‑20)**, and other **TRC‑20 / TRC‑10** tokens, plus TRON resources (Energy & Bandwidth). The app also includes TRON test networks (Nile, Shasta) for developers — **Mainnet** is real TRX.

### How do I add a token to my wallet?

You don't need to. SaveWallet reads balances directly from TRON, so standard TRC‑20 tokens you hold appear automatically. See [How tokens appear](../mobile-app/assets-management/how-to-add-a-token.md).

### Is my recovery phrase ever uploaded or shared?

Never. It's created and kept on your device only. SaveWallet will never ask you for it, and you should never enter it on any website or share it with anyone.

### Need more help?

Contact the team by email at [admin@tronsave.io](mailto:admin@tronsave.io) or on Telegram via the official bot, [@savewalletofficial\_bot](https://t.me/savewalletofficial_bot).
