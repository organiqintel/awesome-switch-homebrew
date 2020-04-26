# Awesome Nintendo Switch Homebrew

A curated collection of awesome things related to Nintendo Switch hacking and homebrew.

## Contents

- [Documentation](#documentation)
  - [Guides](#guides)
- [Hardware](#hardware)
  - [Payload Injectors](#external-hardware)
  - [Modchips](#modchips)
- [System Software](#system-software)
  - [Bootloaders](#bootloaders)
  - [Payloads](#payloads)
  - [Custom Firmware](#custom-firmware)
  - [Operating Systems](#operating-systems)
- [Homebrew](#homebrew)
  - [System Modules](#system-modules)
  - [Tesla Overlays](#tesla-overlays)
  - [Utilities](#utilities)
  - [Games](#games)
  - [Games (8.1.0)](#games-8.1.0)
  - [Emulation](#emulation)
  - [Media and Streaming](#media-and-streaming)

## Documentation

### Guides

- [Nintendo Homebrew Switch Guide](https://nh-server.github.io/switch-guide/) - Excellent getting started guide to Nintendo Switch hacking, maintained by Nintendo Homebrew Discord Server
- [Sending a Payload](https://nh-server.github.io/switch-guide/user_guide/sysnand/sending_payload/) - Overview of various methods of sending payloads to the Switch
- [SAMD21 Modchip Install Guide](https://gbatemp.net/threads/internal-modchip-samd21-trinket-m0-gemma-m0-itsybitsy-m0-express-guide-files-support.508068/) - Install guide for Trinket M0, Rebug SwitchME M0, etc.

## Hardware

**Warning**: Please use caution when purchasing any console hacking/modding products online.

### Payload Injectors

- [NS-Atmosphere](http://www.ns-atmosphere.com/en/)
- [RCMloader](https://www.xkit.xyz/rcmloader/), [RCMloader zero](https://www.xkit.xyz/rcmloader-zero/)
- [SX Pro](https://sx.xecuter.rocks/#prod-sxpro) - Comes with SX OS license

### Modchips

- [Trinket M0](https://www.adafruit.com/product/3500), [Gemma M0](https://www.adafruit.com/product/3501), [ItsyBitsy M0 Express](https://www.adafruit.com/product/3727), [Feather M0 Express](https://www.adafruit.com/product/3403) - SAMD21-based microcontroller boards from Adafruit that can be used as modchips in unpatched Switches
- [Rebug SwitchME M0](https://github.com/Aboshi/SwitchME) - An open source SAMD21-based modchip designed for use in unpatched Switches

## System Software

### Bootloaders

- [TegraRcmGUI](https://github.com/eliboa/TegraRcmGUI) - Windows utility to inject payloads in RCM mode
- [Hekate](https://github.com/CTCaer/hekate) - Custom Nintendo Switch bootloader, firmware patcher, and more
- [Fusee_Suite](https://gbatemp.net/threads/trinket-rebug-others-modchip-software-new-fusee_suite-uf2-packages.553998/) - Firmware for SAMD21-based modchips

### Payloads

- [Incognito_RCM](https://github.com/jimzrt/Incognito_RCM) - Utility to remove console serial number from sysnand or emunand
- [Lockpick_RCM](https://github.com/shchmue/Lockpick_RCM) - Utility for dumping console encryption keys

### Custom Firmware

- [Atmosphere](https://github.com/Atmosphere-NX/Atmosphere) - Open source custom firmware for Nintendo Switch
- [SX OS](https://sx.xecuter.rocks/) - Commercial custom firmware for Nintendo Switch

### Operating Systems

- [L4T Ubuntu](https://gbatemp.net/threads/l4t-ubuntu-a-fully-featured-linux-on-your-switch.537301/) - Ubuntu Linux based on NVIDIA's Linux for Tegra project
- [Lakka](https://lakka-switch.github.io/documentation/) - L4T Ubuntu build focused on emulation using RetroArch as the frontend
- [LineageOS](https://forum.xda-developers.com/nintendo-switch/nintendo-switch-news-guides-discussion--development/rom-switchroot-lineageos-15-1-t3951389) - LineageOS (Android) for Nintendo Switch

## Homebrew

Note that a lot of the apps listed below can be installed via the Homebrew App Store.

### Utilities

- [nx-hbmenu](https://github.com/switchbrew/nx-hbmenu) - Nintendo Switch Homebrew Menu, comes bundled with Atmosphere
- [Homebrew App Store](https://github.com/vgmoose/hb-appstore) - GUI for downloading/managing homebrew apps
- [Awoo Installer](https://github.com/Huntereb/Awoo-Installer) - Title installer for Nintendo Switch
- [Checkpoint](https://github.com/FlagBrew/Checkpoint) - Fast and simple homebrew save manager
- [ChoiDujourNX](https://switchtools.sshnuke.net/) - Firmware update utility
- [EdiZon](https://github.com/WerWolv/EdiZon) - A homebrew save management, editing tool and memory trainer
- [Goldleaf](https://github.com/XorTroll/Goldleaf) - Multipurpose homebrew tool (file browser, title installer)
- [Kosmos Toolbox](https://github.com/AtlasNX/Kosmos-Toolbox) - A toolbox for the Kosmos CFW package that contains some useful utilities (enable/disable sysmodules, set override key, reboot to payload)
- [nxdumptool](https://github.com/DarkMatterCore/nxdumptool) - Cartridge and eShop title dumping utility
- [NX-Shell](https://github.com/joel16/NX-Shell) - File manager
- [NXThemes Installer](https://github.com/exelix11/SwitchThemeInjector) - Switch theme manager
- [Payload Launcher](https://github.com/suchmememanyskill/Payload_Launcher) - Reboot to payload utility with a nice user interface

### System Modules

- [nx-ovlloader](https://github.com/WerWolv/nx-ovlloader) - Host process for loading Switch overlay OVLs
- [sys-clk](https://github.com/retronx-team/sys-clk) - CPU and GPU overclocking system module
- [sys-con](https://github.com/cathery/sys-con) - Nintendo Switch sysmodule that allows support for third-party controllers
- [sys-ftpd-light](https://github.com/cathery/sys-ftpd-light) - FTP server system module
- [sys-tune](https://github.com/HookedBehemoth/sys-tune) - Background audio player for the Nintendo switch

### Tesla Overlays

- [Tesla Menu](https://github.com/WerWolv/Tesla-Menu) - Base overlay required to load child overlays
- [Status Monitor Overlay](https://github.com/masagrator/Status-Monitor-Overlay) - Monitor many stats of Nintendo Switch hardware
- [sys-clk-Overlay](https://github.com/Sun-Research-University/sys-clk-Overlay) - Overlay for managing sys-clk system module settings

### Games

- [Cave Story Engine 2](https://github.com/heyjoeway/Cave-Story-Engine-2) - Enhanced port of the Cave Story Engine 2
- [DevilutionX](https://github.com/lantus/devilution-nx) - Diablo for the Nintendo Switch
- [Doom64 EX](https://github.com/fgsfdsfgs/Doom64EX) -  Nintendo Switch port Doom64 EX
- [EDuke32](https://github.com/fgsfdsfgs/eduke32) -  Nintendo Switch port EDuke32
- [GZDoom](https://github.com/fgsfdsfgs/gzdoom/tree/switch) - 3D-accelerated Doom source port
- [Postal-NX](https://github.com/Sch-LikA/postal-nx) - Nintendo Switch port of Postal

### Games (8.1.0)

These games only work on firmware up to version 8.1.0 due to Nintendo changing the way inputs are handled in 9.0.0.

- [NXQuake2](https://github.com/fgsfdsfgs/nxquake2) - Nintendo Switch port of the Yamagi Quake II client
- [OpenLara](https://github.com/XProger/OpenLara) - Classic Tomb Raider open-source engine
- [QuakespasmNX](https://github.com/fgsfdsfgs/QuakespasmNX) - Nintendo Switch port of Quakespasm
- [Taisei Project](https://taisei-project.org/) - Awesome bullet hell shoot'em up
- [Wolf4SDL-Switch](https://github.com/keeganatorr/Wolf4SDL-Switch) - Enhanced port of Wolfenstein 3D

### Emulation

- [RetroArch](https://www.retroarch.com/?page=platforms) - Multi-platform emulation framework
- [PPSSPP](https://www.ppsspp.org/downloads.html) - Standalone PSP emulator
- [pemu (pFBN, pNES, pSNES)](https://github.com/Cpasjuste/pemu) - Suite of standalone emulators by Cpasjuste

### Media and Streaming

- [SKyNX](https://github.com/DevL0rd/SkyNX) - PC game streaming
