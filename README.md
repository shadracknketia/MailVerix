# 📧 MailVerix: High-Speed Email Verification Engine

![Version](https://img.shields.io/badge/version-1.1.0-blue)
![Platform](https://img.shields.io/badge/platform-Windows-blue)
![License](https://img.shields.io/badge/license-Freemium-green)

**MailVerix** is a professional-grade Windows desktop application designed for high-volume email list cleaning. It combines speed with accuracy using a dual-pipeline architecture.

[🚀 Download Latest Installer](https://github.com/shadracknketia/MailVerix/releases) | [🌐 Official Website](https://smartivatepro.com)

---

## ✨ Key Features

*   **Dual-Mode Verification:**
    *   **Fast Verify (Scenario B):** Rapid DNS and MX record checking. Cleans 1M+ lists in minutes.
    *   **Smart Verify (Scenario C):** Deep-level SMTP Handshakes with Catch-all detection.
*   **Data Preservation:** Import CSV or Excel files. MailVerix verifies the emails while keeping all your original columns (Names, Phones, etc.) intact.
*   **Selective SMTP Logic:** Automatically skips sensitive providers (Gmail, Outlook, AOL) to protect your IP reputation.
*   **Real-time Dashboard:** Visual counters for Valid, Invalid, Risky, and Processed leads.
*   **High Concurrency:** Powered by `asyncio`, processing up to 100 emails simultaneously.

---

## 🛠 Technical Stack

- **UI:** PyQt5 (Optimized for Windows Server compatibility)
- **Engine:** Python 3.12 + Asyncio
- **Data Handling:** Pandas & OpenPyXL
- **Database:** SQLite (Local Caching)
- **Security:** Hardware ID (HWID) Locking via Smartivate API

---

## 🚀 Getting Started

### Installation
1. Download the `MailVerix_Setup.exe` from the [Releases](https://github.com/shadracknketia/MailVerix/releases) section.
2. Run the installer. Since the app is currently independent, click **"More Info"** -> **"Run anyway"** on the Windows SmartScreen.
3. Activate your license or continue with the **Free Trial** (50 emails/session).

### Usage
1. Click **Import** to load your `.txt`, `.csv`, or `.xlsx` file.
2. Choose your preferred tab (Fast or Smart).
3. Click **Start Verification**.
4. Once finished, click **Export** to save your clean list.

---

## 🔐 Licensing
MailVerix follows a Freemium model:
- **Free Trial:** 50 verifications per session + Export Watermark.
- **Solo Pro:** Unlimited verifications for 1 device.
- **Agency Pro:** Unlimited verifications for 5 devices.

Purchase a license key at: [smartivatepro.com/products/mailverix](https://smartivatepro.com/products/mailverix)

---

## 📞 Support
- **Support Portal:** [smartivatepro.com/support](https://smartivatepro.com/support)
- **Email:** support@smartivatepro.com

© 2026 Smartivate. All rights reserved.
