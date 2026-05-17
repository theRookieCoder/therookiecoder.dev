+++
title = "Setup"
modified = 2026-05-17
author = "theRookieCoder"
tags = []
+++

# Hardware

## Computer (Laptop)

I use the [Framework](https://frame.work) [Laptop 13](https://frame.work/laptop13), specifically the Ryzen 7040 series from 2023.

| Com&shy;ponent | Spec              |
| -------------- | ----------------- |
| CPU            | [AMD Ryzen 7840U] |
| RAM            | DDR5 5600 MHz     |
| Memory         | 2x16 GB           |
| SSD            | WD_BLACK SN850X   |
| Storage        | 1 TB              |
| Keyboard       | US English        |

[AMD Ryzen 7840U]: https://www.amd.com/en/products/processors/laptop/ryzen/7000-series/amd-ryzen-7-7840u.html

The only part of this laptop I have changed is the WiFi card; I replaced the stock MediaTek/AMD RZ616 with an Intel AX210 as I had issues with WiFi connectivity, Linux, and Bluetooth when dual-booting with Windows.

### Expansion Cards

- 2x USB-C
- USB-A
- Ethernet
- HDMI
- microSD card reader

I usually go with a USB-C on both sides for charging, a USB-A with my mouse's wireless receiver on one side and an ethernet port on the other side. I don't use the HDMI port much anymore since many projectors now support USB-C.

### Accessories

| Accessory | Product         |
| --------- | --------------- |
| Mouse     | Ajazz AJ179 Pro |
| Keyboard  | Aula F75        |

I heard that good value gaming mice are available from AliExpress for cheap now so I tried Ajazz. I bought it for €21 but I didn't receive the dock so I got a €7 refund, so in the end I got the mouse for €14.
I also got the keyboard from Temu since my friend tried it and said it's really good.

# Software

For colours I like the [Catppuccin](https://catppuccin.com) theme, specifically the Macchiato flavour. You are seeing it right now because that is what I used to theme this website!

## Operating System

I daily-drive the latest stable version of [Fedora Linux](https://fedoraproject.org), and I have Windows 11 in a dual-boot setup. On Fedora I use KDE as my desktop environment; the only theming I have done is using Catppuccin colours and using [Panel Colorizer](https://github.com/luisbocanegra/plasma-panel-colorizer) but just for window bars.

## Terminal and Package Management

I use [kitty](https://sw.kovidgoyal.net/kitty) as my terminal on Linux and macOS, and [Windows Terminal](https://aka.ms/terminal) on Windows. For shells, I use [fish](https://fishshell.com) on Linux and macOS, and [Nushell](https://nushell.sh) and PowerShell on Windows. Checkout my [dotfiles](https://github.com/theRookieCoder/dotfiles) to see how I configure *fish* and *kitty*.

On Fedora I use `dnf`, and on Debian derivatives like Ubuntu I like to use [Nala](https://github.com/volitank/nala) as the APT frontend. My second choice is [Flatpaks](https://flatpak.org) from [Flathub](https://flathub.org). If none of those are available, I install and manage AppImages using [Gear Lever](https://flathub.org/en/apps/it.mijorus.gearlever).

On Windows, I use [WinGet](https://learn.microsoft.com/en-us/windows/package-manager) and rarely [Scoop](https://scoop.sh). And on macOS, I use [Homebrew](https://brew.sh).

## Browser (Firefox)

I use [Firefox](https://mozilla.org/firefox) as my browser, these are the add-ons I use

- [Bitwarden](https://addons.mozilla.org/en-US/firefox/addon/bitwarden-password-manager) password manager
- [uBlock Origin](https://addons.mozilla.org/en-US/firefox/addon/ublock-origin) ad blocker
- [Stylus](https://addons.mozilla.org/en-US/firefox/addon/styl-us) theming for websites
- [Firefox Color](https://addons.mozilla.org/en-US/firefox/addon/firefox-color) theming for Firefox's UI
- [LanguageTool](https://addons.mozilla.org/en-US/firefox/addon/languagetool) spelling/grammar checker
- [SponsorBlock](https://addons.mozilla.org/en-US/firefox/addon/sponsorblock) skip sponsor sections in YouTube videos
- [Unhook](https://addons.mozilla.org/en-US/firefox/addon/youtube-recommended-videos) hide YouTube recommendations
- [Vimium](https://addons.mozilla.org/en-US/firefox/addon/vimium-ff) vim-motions when navigating websites
- [SteamDB](https://addons.mozilla.org/en-US/firefox/addon/steam-database) see price history in the Steam store page

## <abbr title="Integrated Development Environment">IDE</abbr>

I primarily use [Visual Studio Code](https://code.visualstudio.com). These are the extensions I use, excluding language-specific ones

- [Catppuccin](https://marketplace.visualstudio.com/items?itemName=Catppuccin.catppuccin-vsc) and [Catppuccin Perfect Icons](https://marketplace.visualstudio.com/items?itemName=thang-nm.catppuccin-perfect-icons)
- [Error Lens](https://marketplace.visualstudio.com/items?itemName=usernamehw.errorlens)
- [GitHub Actions](https://marketplace.visualstudio.com/items?itemName=github.vscode-github-actions) and [GitHub Pull Requests](https://marketplace.visualstudio.com/items?itemName=GitHub.vscode-pull-request-github)
- [Live Share](https://marketplace.visualstudio.com/items?itemName=ms-vsliveshare.vsliveshare)
- [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)
- [Even Better TOML](https://marketplace.visualstudio.com/items?itemName=tamasfe.even-better-toml)
- [Remote Explorer](https://marketplace.visualstudio.com/items?itemName=ms-vscode.remote-explorer) and [Remote - SSH](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-ssh)

I also use [JetBrains'](https://jetbrains.com) [IntelliJ IDEA](https://jetbrains.com/idea) for Java and sometimes [RustRover](https://jetbrains.com/rust) for Rust. These are the extensions I use

- [Catppuccin Theme](https://plugins.jetbrains.com/plugin/18682-catppuccin-theme)
- [Catppuccin Icons](https://plugins.jetbrains.com/plugin/23029-catppuccin-icons)
- [VSCode Keymap](https://plugins.jetbrains.com/plugin/12062-vscode-keymap)
