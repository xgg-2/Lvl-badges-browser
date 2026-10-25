# MAX UR BADGES - In Browser 

A fast, lightweight, and zero-dependency browser snippet designed to simulate game activity, boost played games count, and register thousands of hours across all detectable Discord games using Discord's internal Science telemetry API.

---

## Features

- **No Python or Termux Required:** Runs natively inside your browser's Developer Console.
- **Maximum Boost:** Automatically targets all 10,000+ detectable Discord games at 10,000 hours per game.
- **Mobile Friendly:** Fully compatible with Android using **Kiwi Browser**.
- **Safe & Batched:** Groups events into requests of 50 games per payload with adaptive delay to avoid rate-limits.

---

## Prerequisites & Installation

### Option 1: Mobile (Android via Kiwi Browser)

Since mobile Chrome does not support Developer Tools, you must use **Kiwi Browser**, a Chromium-based Android browser with full Developer Tools support.

1. **Download Kiwi Browser:**
   - Download the latest APK from the [Official Kiwi Browser GitHub Releases](https://github.com/kiwibrowser/src.next/releases).
2. **Login to Discord:**
   - Open Kiwi Browser and navigate to [https://discord.com/app](https://discord.com/app).
   - Log into your Discord account.
3. **Open Developer Tools:**
   - Tap the three dots (`⋮`) menu in the top-right corner.
   - Scroll down and tap **Developer Tools**.
   - Select the **Console** tab in the developer window.

---

### Option 2: Desktop (Windows, macOS, Linux)

1. Open your web browser (Chrome, Edge, Brave, or Firefox).
2. Navigate to [https://discord.com/app](https://discord.com/app) and log into your account.
3. Open the Developer Console:
   - **Windows/Linux:** Press `F12` or `Ctrl + Shift + I`, then click the **Console** tab.
   - **macOS:** Press `Cmd + Option + I`, then click the **Console** tab.

---

## How to Run

1. Copy the contents of `script.js`.
2. Paste the entire script directly into the **Console** tab.
3. Press **Enter**.

The script will automatically authenticate your session, fetch the official games database, and start sending telemetry batches in the background.

---

## Important Notes

> **Notice:** Profile statistics, playtime counters, and profile badges take approximately **24 hours** to sync across Discord servers. Do not panic if your profile stats do not update immediately after completion!

---

## Disclaimer

> This tool is created strictly for educational and research purposes. Using automated scripts or self-bots on Discord accounts violates Discord's Terms of Service. Use this tool responsibly at your own risk.
