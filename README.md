<p align="center">
  <img src="assets/logo.png" alt="Miqat Logo" width="140" style="border-radius: 24px;" />
</p>

<h1 align="center">Miqat Releases 📱✨</h1>

<p align="center">
  <strong>The official distribution & release repository for the Miqat mobile application.</strong>
</p>

<p align="center">
  <a href="#-latest-releases"><img src="https://img.shields.io/badge/Latest%20Version-v1.0.0-0d9488?style=for-the-badge&logo=rocket" alt="Latest Version" /></a>
  <a href="#-android-apk"><img src="https://img.shields.io/badge/Platform-Android-34D399?style=for-the-badge&logo=android&logoColor=white" alt="Android" /></a>
  <img src="https://img.shields.io/badge/Platform-iOS%20(Coming%20Soon)-0ea5e9?style=for-the-badge&logo=apple&logoColor=white" alt="iOS" />
  <img src="https://img.shields.io/badge/Status-Active-22c55e?style=for-the-badge" alt="Status Active" />
</p>

---

## 📌 Overview

Welcome to the official **Miqat (مِيقات)** releases repository! This repository hosts production and staging application packages, over-the-air (OTA) update manifests, and direct download links for Android and iOS devices.

Whether you are downloading the latest package directly or checking for in-app updates, this repository serves as the central release hub.

---

## 🚀 Latest Releases

| Platform | Latest Version | Package / Asset | Direct Link | Status |
| :--- | :---: | :--- | :---: | :---: |
| **Android** | `v1.0.0` | `miqat-v1.0.0.apk` | [⬇️ Download APK](https://github.com/mohammednabi/miqat-releases/releases/tag/v1.0.0) | 🟢 Stable |
| **iOS** | — | *In Development* | ⏳ *Coming Soon* | 🟡 Planned |

<!--
Uncomment when iOS release is ready:
| **iOS** | `v1.0.0` | `manifest.plist` | [📋 View Manifest](./ios/manifest.plist) | 🟡 Setup |
-->

> [!TIP]
> Always download releases directly from this repository or verified distribution channels to ensure authenticity and file integrity.

---

<!-- ## 📂 Repository Structure

```text
miqat-releases/
├── android/
│   └── miqat-v1.0.1.apk       # Standalone Android installer package (APK)
├── ios/
│   └── manifest.plist         # Apple Over-the-Air (OTA) deployment manifest
├── assets/
│   └── logo.png               # Official branding and icons
└── README.md                  # Release documentation & download guides
``` -->

<!-- --- -->

## 📲 Installation Instructions

### 🤖 Android (.apk)

1. **Download the APK**: Download the latest build from [`android/miqat-v1.0.0.apk`](https://github.com/mohammednabi/miqat-releases/releases/tag/v1.0.0).
2. **Allow Installation from Unknown Sources**:
   - On Android 8.0+: When prompted by your browser or file manager, tap **Settings** and toggle **Allow from this source**.
   - On older versions: Go to **Settings > Security > Unknown Sources** and enable it.
3. **Install**: Open the downloaded `.apk` file and tap **Install**.
4. **Launch**: Once installation finishes, tap **Open** to start using Miqat.

<!-- ---

### 🍏 iOS (OTA / Manifest)

For enterprise or ad-hoc test distribution:

1. **Safari Direct Install**: Open the OTA link in Safari using the `itms-services` protocol:
   ```text
   itms-services://?action=download-manifest&url=https://raw.githubusercontent.com/<YOUR-USERNAME>/miqat-releases/main/ios/manifest.plist
   ```
2. **Trust Enterprise Profile** _(if prompted)_:
   - Go to **Settings > General > VPN & Device Management**.
   - Select the Enterprise/Developer profile for Miqat and tap **Trust**.
3. **Launch the App**: Open Miqat from your home screen. -->

---

## 🔄 Release Notes & Changelog

### `v1.0.0` (Current Stable)

- ✨ Initial public release build.
- ⚡ Core functionality, UI enhancements, and performance optimizations.
- 🛠️ In-app update check support.
- 📱 Cross-platform stability improvements.

---

## 🛡️ Security & Verification

We recommend verifying package integrity before installation:

- **Official Source**: Verify you are downloading from the verified repository.
- **Permissions**: Miqat requests only necessary permissions required for app functionality (e.g. notifications, location).

---

## 💬 Support & Feedback

If you encounter any issues during download or installation, or if you'd like to suggest an improvement:

- 🐛 **Report an Issue**: Open an issue on GitHub or submit feedback through the app.
- 📧 **Inquiries**: Reach out to the Miqat development team.

<p align="center">
  <sub>Built with care for the <strong>Miqat</strong> community.</sub>
</p>
