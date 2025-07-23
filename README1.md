# 💼 DaWallet-V1-offline

**Offline Bitcoin Watch-Only Wallet & PSBT Management Tool with QR Code Support**

This is a fully offline-capable HTML tool designed for managing Bitcoin watch-only descriptors, generating `importdescriptors` commands, and creating QR codes for airgapped workflows. It runs entirely in your browser without internet access, making it ideal for cold wallet setups or secure environments.

---

## 📂 Features

- 🔐 **Offline-first**: No internet required to function. Secure by design.
- 🧾 **Descriptor Import Helper**: Convert JSON from `listdescriptors` into ready-to-paste `importdescriptors` RPC commands.
- 📦 **QR Code Generator**: Encode any text into a QR code using the included offline script.
- 🎨 **Custom UI**: Clean interface with a themed background for Bitcoin enthusiasts.

---

## 🛠️ Usage

1. Open `DaWallet-V1-offline.html` in any modern browser (fully offline).
2. Use the **Generic QR Generator** section to convert text into QR codes.
3. Use the **Descriptor Management** section to:
   - Paste your `listdescriptors` JSON output.
   - Generate corresponding `importdescriptors` commands.
   - Copy with a click.

> 🔒 Your data never leaves the local machine. No network requests are made.

---

## 📁 Files Included

| File | Description |
|------|-------------|
| `DaWallet-V1-offline.html` | Main interface with embedded QR and descriptor tools |
| `qrcode.min.js` | QR code generator script (included locally) |
| `future-btc-home.jpg` | Futuristic Bitcoin-themed background image |

---

## 📜 Dependencies and Credits

This tool uses the excellent open-source library:

- [QRCode.js by davidshimjs](https://github.com/davidshimjs/qrcodejs/blob/master/qrcode.min.js)

Licensed under MIT. Embedded in the local folder to ensure offline compatibility.

---

## 🧠 Notes

- Tested on Chromium-based browsers and Firefox.
- Ensure all files remain in the same folder (`.html`, `.js`, `.jpg`) for proper background and QR functionality.
- No server, no tracking, no dependencies—just raw Bitcoin tools.

---

## 🧡 Built for Bitcoiners

> “Not your keys, not your coins. Not your node, not your rules.”  
> This tool was created for maximum sovereignty and cold storage workflows.