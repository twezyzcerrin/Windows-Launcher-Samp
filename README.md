# Virulent Launcher for SA-MP

A modern, high-performance, and fully customizable launcher for GTA San Andreas Multiplayer (SA-MP) servers. Built with Electron and React, this launcher offers a sleek design, Discord Rich Presence integration, and a seamless user experience for your community.

![Launcher Preview](./launcher.png)

## 🚀 Features

*   **Modern UI/UX**: A clean, tablet-sized interface (1024x768) with a dark, glass-morphism aesthetic built using Tailwind CSS.
*   **Real-Time Server Stats**: Automatically fetches and displays online players, maximum slots, and server latency (ping).
*   **Discord Rich Presence (RPC)**: built-in integration to show your server's status on players' Discord profiles (customizable images, text, and player counts).
*   **Anti-Cheat Integration**: Displays "Anti-Cheat Active" status to reassure players (visual indicator).
*   **Secure Game Launch**: Uses detached process spawning to bypass common antivirus false positives and ensures clean game injection.
*   **User Settings Management**: 
    *   Automatic detection of GTA San Andreas installation path.
    *   Saves player nickname and settings locally.
    *   User-friendly settings modal.
*   **Customizable Configuration**: easily change server IP, port, name, and links via a simple `config.json` file.
*   **Auto-Updater Ready**: Built on Electron structure that supports future integration with auto-update systems.

## 🛠️ Customization

You can easily rebrand this launcher for your own server by editing the `config.json` file or the source code:

*   **Server Name & Description**
*   **IP Address & Port**
*   **Social Links (Discord, Twitter, Website)**
*   **Background Images & Logos**
*   **Color Scheme (via Tailwind)**

## 📦 Installation & Setup

### Prerequisites
*   Node.js (v16 or higher)
*   npm (Node Package Manager)

### Development
1.  Clone the repository:
    ```bash
    git clone https://github.com/yourusername/virulent-launcher.git
    cd virulent-launcher
    ```
2.  Install dependencies:
    ```bash
    npm install
    ```
3.  Run the development server:
    ```bash
    npm start
    ```

### Building for Production
To create a distributable `.exe` installer for Windows:

```bash
npm run build:win
```
The installer will be located in the `dist/` folder.

## 💰 Licensing & Purchase

This source code is available for **$15 USD**. 

**What you get:**
*   Full unencrypted source code.
*   Right to modify and distribute for your own server.
*   Basic support for setup.

**Purchase Link**: [Insert Your Purchase Link Here]
**Contact**: [Insert Your Discord/Contact Info Here]

---
*Note: This launcher is a standalone application and requires a valid installation of GTA San Andreas and SA-MP on the user's machine.*

