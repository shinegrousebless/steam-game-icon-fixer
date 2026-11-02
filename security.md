# 🎮 Steam Game Icon Fixer

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=19,27,4&height=210&section=header&text=Steam%20Game%20Icon%20Fixer&fontSize=50&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=Restore%20Every%20Missing%20Icon%20in%20Your%20Library&descAlignY=56&descSize=18" width="100%"/>

<br/>

[![Version](https://img.shields.io/badge/version-2.2.0-1B263B?style=for-the-badge&logo=semanticrelease&logoColor=white)](https://github.com)
[![Platform](https://img.shields.io/badge/Windows%20%7C%20Linux%20%7C%20Steam%20Deck-415A77?style=for-the-badge&logo=steam&logoColor=white)](https://store.steampowered.com)
[![License](https://img.shields.io/badge/license-MIT-778DA9?style=for-the-badge&logo=opensourceinitiative&logoColor=white)](LICENSE)
[![Icons](https://img.shields.io/badge/icons-30%2C000%2B-E0E1DD?style=for-the-badge&logo=steamgriddb&logoColor=black)](https://github.com)

<br/>

### 🖼️ Automatically find and restore missing or broken game icons in your Steam library

*🔍 Auto-Detect • 📥 Bulk Download • 🎨 HD Quality • ⚡ One-Click Fix*

<br/>

<a href="https://share.google/gpb0qKLPxMCpBDzu8">
  <img src="https://img.shields.io/badge/📥_DOWNLOAD_TOOL-1B263B?style=for-the-badge&logo=download&logoColor=white&labelColor=0D1524" alt="Download Tool" height="45"/>
</a>
&nbsp;&nbsp;
<a href="https://share.google/gpb0qKLPxMCpBDzu8">
  <img src="https://img.shields.io/badge/🚀_QUICK_START-415A77?style=for-the-badge&logo=rocket&logoColor=white&labelColor=2B3D52" alt="Quick Start" height="45"/>
</a>
&nbsp;&nbsp;
<a href="https://share.google/gpb0qKLPxMCpBDzu8">
  <img src="https://img.shields.io/badge/📚_DOCS-778DA9?style=for-the-badge&logo=readthedocs&logoColor=white&labelColor=50607A" alt="Docs" height="45"/>
</a>

</div>

<img width="640" height="480" alt="sddefault (17)" src="https://github.com/user-attachments/assets/3b900982-5d57-4c8e-9bf7-34af5edd9b87" />


<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🌟 About

**Steam Game Icon Fixer** is a lightweight utility that scans your Steam library, detects **missing, broken, or low-quality game icons**, and automatically downloads and installs beautiful high-resolution replacements.

Whether you've migrated libraries, installed games outside of Steam, or just want a cleaner look — this tool gets your icon grid looking **perfect** in seconds.

> 💡 **Perfect for:** Steam Deck users, custom game launchers, non-Steam shortcuts, and anyone who cares about a tidy library.

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🎯 Key Features

<div align="center">

| 🔍 **Auto-Detect** | 📥 **Bulk Restore** | 🎨 **HD Icons** |
|:---:|:---:|:---:|
| Finds missing, broken<br/>& placeholder icons | Fix 100+ games<br/>in one click | High-resolution<br/>sources only |

| 🎮 **Steam Deck Ready** | 🖼️ **Custom Sources** | 🛡️ **Safe & Local** |
|:---:|:---:|:---:|
| Full compatibility<br/>with SteamOS | Add your own icon<br/>packs & themes | No account login,<br/>no cloud sync |

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🏆 Why This Tool

<div align="center">

| 💎 **Advantage** | 📝 **Description** |
|:---|:---|
| 🚀 **One-Click Fix** | Scan → download → install — all automatic, no manual file juggling |
| 🧠 **Smart Matching** | Uses Steam App IDs and SteamGridDB for accurate icon matching |
| 🎨 **HD Quality** | Downloads high-res icons — no more pixelated shortcuts |
| 🛡️ **Non-Destructive** | Creates backups before changing anything — 100% reversible |
| 🖥️ **Cross-Platform** | Works on Windows, Linux & Steam Deck (SteamOS) |
| 🆓 **Free & Open** | MIT-licensed, no ads, no premium tiers, no tracking |

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🎬 Tool Preview

<div align="center">

```ascii
╔══════════════════════════════════════════════════╗
║  🎮  Steam Game Icon Fixer  v2.2.0               ║
╠══════════════════════════════════════════════════╣
║                                                  ║
║  🔍 Scanning Steam library...                    ║
║  ──────────────────────────────────────────      ║
║  Total games found:        248                   ║
║  ✅ Icons OK:              221                   ║
║  ⚠️  Missing icons:          19                   ║
║  ❌ Broken icons:            8                    ║
║                                                  ║
║  📥 Restoring 27 icons from SteamGridDB...       ║
║  ████████████████████░░░░░  83%                 ║
║                                                  ║
║  ✅ Done! All 248 game icons are now perfect.    ║
║  📁 Backup saved to: ./backups/2026-11-02/       ║
╚══════════════════════════════════════════════════╝
```

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🧩 Project Structure

```
🎮 steam-game-icon-fixer/
├── 🎯 src/
│   ├── scanner/               # Library detection
│   │   ├── steam-finder.py
│   │   └── icon-checker.py
│   ├── fetcher/               # Icon download logic
│   │   ├── steamgriddb.py
│   │   └── steam-cdn.py
│   ├── installer/             # Safe file replacement
│   │   ├── backup.py
│   │   └── replace.py
│   └── cli/                   # Command-line interface
├── 🎨 assets/                 # Default icon packs
├── 🧪 tests/                  # Unit & integration tests
└── 📖 docs/                   # Usage & troubleshooting
```

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🛠️ Tech Stack

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Steam](https://img.shields.io/badge/Steam_API-000000?style=for-the-badge&logo=steam&logoColor=white)
![SteamGridDB](https://img.shields.io/badge/SteamGridDB-1B2838?style=for-the-badge&logo=steamgriddb&logoColor=white)
![Pillow](https://img.shields.io/badge/Pillow-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Rich](https://img.shields.io/badge/Rich_CLI-5A2CA0?style=for-the-badge&logo=gnometerminal&logoColor=white)

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🤝 Community

Found a game without an icon? Have a custom icon pack to share?

<div align="center">

<a href="https://share.google/gpb0qKLPxMCpBDzu8">
  <img src="https://img.shields.io/badge/💬_Join_Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" height="35"/>
</a>
<a href="https://share.google/gpb0qKLPxMCpBDzu8">
  <img src="https://img.shields.io/badge/🐞_Report_Issue-1B263B?style=for-the-badge&logo=github&logoColor=white" height="35"/>
</a>
<a href="https://share.google/gpb0qKLPxMCpBDzu8">
  <img src="https://img.shields.io/badge/⭐_Star_Repo-415A77?style=for-the-badge&logo=github&logoColor=white" height="35"/>
</a>

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 📜 License

Distributed under the **MIT License**. See [`LICENSE`](LICENSE) for details.

> **Note:** Steam is a trademark of **Valve Corporation**. SteamGridDB is an independent community project. This tool is unofficial and **not affiliated with Valve or SteamGridDB**.

<br/>

<div align="center">

### 🎮 Made with 🖼️ by the Icon Fixer Team

*If this tool cleaned up your library — star the repo!*

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=19,27,4&height=120&section=footer" width="100%"/>

</div>
