# 📂 GiggleShare

GiggleShare is a **cross-platform file sharing app** built with **React Native** and **Expo**.  
It allows users to **upload files** from their device and **retrieve them** easily, with a clean tab-based interface.

---

## ✨ Features
- 📤 **Upload Files** — Pick and upload documents or media from your device.
- 📥 **Retrieve Files** — Download or view previously uploaded files.
- 📱 **Cross-Platform** — Works on **Android**, **iOS**, and **Web** (via Expo).
- 🎨 **Modern UI** — Powered by React Navigation and vector icons.
- ⚡ **Fast & Secure** — File handling with Expo's native APIs and Socket.IO.

---

## 🛠 Tech Stack
- **Framework**: [React Native](https://reactnative.dev/) + [Expo](https://expo.dev/)
- **Navigation**: [React Navigation](https://reactnavigation.org/)
- **UI Icons**: [React Native Vector Icons](https://github.com/oblador/react-native-vector-icons)
- **File Handling**: Expo Document Picker, Expo Media Library, Expo Sharing
- **Networking**: Axios, Socket.IO
- **Other Tools**: Crypto-JS, UUID

---

## 📂 Project Structure
giggleshare/
├── App.js # Main navigation with bottom tabs
├── index.js # App entry point
├── screens/ # Upload and GetFile screen components
├── assets/ # App icons, splash images, and assets
├── app.json # Expo configuration
├── eas.json # EAS build configuration
├── package.json # Dependencies and scripts
└── .gitignore # Ignored files for Git
