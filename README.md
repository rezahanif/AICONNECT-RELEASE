# AI CONNECT Desktop Releases

<div align="center">

![AI CONNECT Banner](https://raw.githubusercontent.com/rezahanif/AiConnect/main/apps/desktop/public/icon.png)

### The Bridge Between AI Agents and Engineering Software
Connect Claude, ChatGPT, Cursor, and other AI agents directly to desktop engineering software including **Autodesk Revit**, **CSI SAP2000**, **QGIS**, **Ansys CFX**, and **Microsoft Office**.

[**⬇️ Download Latest Installer (.exe)**](https://github.com/rezahanif/AICONNECT-RELEASE/releases/latest/download/AiConnect-Setup.exe)

[![Latest Release](https://img.shields.io/github/v/release/rezahanif/AICONNECT-RELEASE?style=for-the-badge&color=blue)](https://github.com/rezahanif/AICONNECT-RELEASE/releases/latest)
[![Platform](https://img.shields.io/badge/platform-Windows%2010%20%7C%2011%20x64-0078D6?style=for-the-badge&logo=windows)](https://github.com/rezahanif/AICONNECT-RELEASE/releases/latest)
[![License](https://img.shields.io/badge/license-MIT-green?style=for-the-badge)](https://github.com/rezahanif/AICONNECT-RELEASE)

</div>

---

## ⚡ Quick Download

| Asset | Platform | Download Link |
|---|---|---|
| **AI CONNECT Setup (.exe)** | Windows 10/11 (64-bit) | [**Download Latest**](https://github.com/rezahanif/AICONNECT-RELEASE/releases/latest/download/AiConnect-Setup.exe) |

> [!NOTE]
> The link above will always automatically download the latest official release. For past releases and changelogs, see the [Releases Page](https://github.com/rezahanif/AICONNECT-RELEASE/releases).

---

## 🚀 Features

- **Automated MCP Server Management**: Local Model Context Protocol (MCP) gateway that manages background connector processes without editing configuration files manually.
- **Bi-directional Engineering Integration**:
  - **Autodesk Revit**: Query BIM element parameters, run Python/C# macros, inspect geometry, extract room & material quantities.
  - **CSI SAP2000**: Run structural analysis, inspect load combinations, retrieve joint & frame member internal forces.
  - **QGIS**: Automate spatial queries, GIS layer filtering, and attribute table analysis.
  - **Ansys CFX**: Automate CFD workflows, solver control, and mesh analysis.
  - **Microsoft Office**: Generate reports, spreadsheets, and documentation.
- **Secure Transactional Connector Installer (CP20)**: All plugins and MCP servers are cryptographically verified and extracted in atomic transactions.
- **Cloud Account & Entitlement Sync**: Seamless authentication with your AI Connect subscription to unlock connectors and skills.

---

## 💻 System Requirements

- **Operating System**: Windows 10 (version 1903 or later) / Windows 11 (64-bit)
- **Processor**: Intel Core i5 / AMD Ryzen 5 or higher recommended
- **Memory**: Minimum 4 GB RAM (8 GB+ recommended when running heavy host engineering applications)
- **Disk Space**: ~500 MB for the base application + additional space for installed connectors

---

## 📦 Installation Guide

1. **Download the installer**:
   Click [**AiConnect-Setup.exe**](https://github.com/rezahanif/AICONNECT-RELEASE/releases/latest/download/AiConnect-Setup.exe).
2. **Run the installer**:
   Double-click `AiConnect-Setup.exe`. The installer will set up AI CONNECT in your user directory (no Administrator privileges required).
3. **SmartScreen Prompt (If applicable)**:
   If Windows Defender SmartScreen displays a warning (*"Windows protected your PC"*):
   - Click **More info**.
   - Click **Run anyway**.
4. **Launch & Connect**:
   Open **AI CONNECT** from your Desktop or Start Menu, log in to your account, and activate the connectors for the software installed on your workstation.

---

## 🛠️ Verification & Checksums

To verify the integrity of the downloaded installer using PowerShell:

```powershell
Get-FileHash -Algorithm SHA256 .\AiConnect-Setup.exe
```

Compare the output hash with the SHA-256 checksum listed on each version's [Release Notes](https://github.com/rezahanif/AICONNECT-RELEASE/releases).

---

## ❓ Troubleshooting & Support

- **Runtime Logs**: If you experience any issues, diagnostic logs can be found at:
  ```text
  %LOCALAPPDATA%\aiconnect\logs
  ```
- **Issues & Feedback**: Submit issues or questions via [GitHub Issues](https://github.com/rezahanif/AICONNECT-RELEASE/issues).
- **Official Website**: [https://aiconnect.fun](https://aiconnect.fun)
