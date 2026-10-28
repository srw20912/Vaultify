# 🛡️ Vaultify

**Vaultify** is a lightweight, secure, and modern desktop application built with Python to encrypt and decrypt sensitive folders and USB sticks. It utilizes robust, industry-standard cryptographic algorithms to keep your private data safe from unauthorized access.

---

## ✨ Features

* **Folder & USB Encryption**: Easily secure entire directories or portable storage devices.
* **AES-256-GCM Encryption**: High-security authenticated encryption powered by Python's `cryptography` library.
* **PBKDF2 Key Derivation**: Protects your master password against brute-force and rainbow table attacks using secure key stretching and salting.
* **Modern GUI**: Clean, user-friendly interface built with `CustomTkinter`.
* **Portable & Standalone**: Compiled into a single Windows `.exe` file via PyInstaller—no Python installation required on the target machine.

---

## 🛠️ Tech Stack

* **Language**: Python 3.x
* **GUI Framework**: [CustomTkinter](https://github.com/TomSchimansky/CustomTkinter)
* **Cryptography**: [Cryptography (AES-256, PBKDF2)](https://cryptography.io/)
* **Packaging**: PyInstaller

---

## 🚀 Getting Started (For Users)

If you just want to use the pre-compiled application:
1. Download the latest `Vaultify.exe` from the [Releases](https://github.com/ jouw-gebruikersnaam/Vaultify/releases) page.
2. Double-click the application to launch.
3. Select your target folder or USB drive, enter a secure password, and encrypt/decrypt!

---

## ⚙️ Development & Installation (For Developers)

If you want to run or modify the source code locally:

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/](https://github.com/) jouw-gebruikersnaam/Vaultify.git
   cd Vaultify