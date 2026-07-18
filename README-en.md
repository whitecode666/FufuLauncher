# [WhitefuLaucher](https://github.com/whitecode666/WhitefuLaucher)

![Platform](https://img.shields.io/badge/Platform-Windows%2010%2F11-brightgreen)
![License](https://img.shields.io/badge/License-MIT-orange)
![.NET](https://img.shields.io/badge/.NET-8.0-blue)
![WinUI](https://img.shields.io/badge/UI-WinUI%203-8A2BE2)

> A third-party Genshin Impact launcher built with WinUI 3, featuring game injection, auto check-in, and various utility tools.

[ä¸­æ–‡](./README.md) | [Tiáº¿ng Viá»‡t](./README-vi.md)

---

## đŸ“¸ Screenshots

> *(Add application screenshots here)*

---

## âœ¨ Features

### đŸ” Account Management
- Quick switching between multiple accounts without re-entering passwords
- Local encrypted storage for account security
- MiHoYo QR code login support

### đŸ“… Auto Check-in
- One-click daily MiHoYo/HoYoLab check-in
- Cloud game check-in support
- Auto community tasks (likes, reads, shares)

### đŸ® Game Management
- Automatic game path detection
- Real-time version update announcements
- Game resource pre-download and integrity verification
- Server switching (Official/Bilibili/Global)

### â¡ Utilities
- **Cultivation Calculator**: Calculate resources needed for characters and weapons
- **Auto Clicker**: Automated keyboard/mouse click operations
- **FPS Monitor**: Real-time in-game frame rate display
- **Screenshot Tool**: One-click game capture
- **Wish History**: View and analyze gacha data
- **Achievement Tracker**: Track achievement progress

### đŸ€ Launch Parameters
- Custom resolution and window mode settings
- Custom launch parameter presets
- Multi-monitor support

### đŸ”§ Injection
- DLL injection support
- Preset management system
- Plugin extension support

### đŸ¨ Customization
- Custom backgrounds (image/video/slideshow)
- Custom theme colors
- Acrylic/Mica backdrop effects
- Adjustable transparency

---

## đŸ“¥ Installation & Usage

### System Requirements
- **OS**: Windows 10/11 (64-bit)
- **Runtime**: [.NET 8.0](https://dotnet.microsoft.com/download/dotnet/8.0) or later
- **Runtime**: [Microsoft Edge WebView2](https://developer.microsoft.com/microsoft-edge/webview2/) (usually pre-installed on Windows 10+)
- **Runtime**: Visual C++ Redistributable v14

### Quick Start

1. **First Launch**: A user agreement will be displayed. Please read and accept it to continue.
2. **Set Game Path**: Go to "Settings" page and select the game installation directory (auto-detection is recommended).
3. **Login**: Log in with your MiHoYo/HoYoLab account on the "Account" page to use check-in features.
4. **Launch Game**: Click "Launch Game" on the main page.

> â ï¸ **Important Notes**:
> - Account switching requires **Administrator privileges**
> - It's recommended to select the game path first, then run the program as Administrator
> - Injection features require **Administrator privileges**
> - Live video backgrounds may be unstable; static images are recommended

---

## đŸ—ï¸ Tech Stack

- **UI Framework**: WinUI 3 (Windows App SDK)
- **Language**: C# (.NET 8.0)
- **Architecture**: MVVM (CommunityToolkit.Mvvm)
- **Database**: SQLite (local settings storage)
- **Injection**: Native DLL injection
- **Backend**: Windows Native APIs + HTTP APIs

---

## đŸ¤ Contributing

Issues and Pull Requests are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Report Issues
- [Report Bug](https://github.com/whitecode666/WhitefuLaucher/issues/new?template=bug_report.yml)
- [Feature Request](https://github.com/whitecode666/WhitefuLaucher/issues/new?template=feature_request.yml)

---

## đŸ“„ License

This project is licensed under the [MIT License](../LICENSE).

Copyright Â© 2026 whitecode666

---

## đŸŒŸ Support

If you find this project helpful, please consider giving it a â­ on GitHub!

[![Star History Chart](https://api.star-history.com/svg?repos=whitecode666/WhitefuLaucher&type=date&legend=top-left)](https://www.star-history.com/#whitecode666/WhitefuLaucher&type=date&legend=top-left)

---

## đŸ“ Contact

- [GitHub Issues](https://github.com/whitecode666/WhitefuLaucher/issues)
- [Telegram](https://github.com/whitecode666/WhitefuLaucher)

---

*This software is an independently developed third-party tool and is not affiliated with miHoYo or its subsidiaries.*
*Please support the official game.*
