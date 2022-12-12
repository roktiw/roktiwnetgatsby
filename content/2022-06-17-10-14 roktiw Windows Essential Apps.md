﻿---
title: "2022-06-17-10-14 roktiw Windows Essential Apps"
metaTitle: "2022-06-17-10-14 roktiw Windows Essential Apps "
metaDescription: "2022-06-17-10-14 roktiw Windows Essential Apps
---

# What to do after installing Windows 10 

## Install Chocolately
Command line package installer
[https://chocolatey.org/](https://chocolatey.org/install)

```
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```

From now on install almost all apps using Chocolately

## Install Web Browser - Google Chrome
Web browser from Google
https://www.google.com/chrome/
```
choco install googlechrome
```


1. Web Browser
1. google-chrome
2. Package installer
1. Choco 
3. Package manager for .zip, .rar files
1. 7zip https://www.7-zip.org/
4. Text editor
1. Visual Studio Code https://code.visualstudio.com/
2. Microsoft Word https://www.microsoft.com/en-ww/microsoft-365/word
3. LibreOffice https://www.libreoffice.org/
5. Graphics
1. GIMP https://www.gimp.org/
2. Inkscape https://inkscape.org/
6. Video and movies
1. VLC https://www.videolan.org/vlc/
7. Recording Audio
1. Audacity https://www.audacityteam.org/
8. Backup and file sharing:
1. Google Drive https://www.google.com/drive/
9. Desktop sharing:
1. TeamViewer https://www.teamviewer.com/en/
10. Clipboard
1. Ditto https://ditto-cp.sourceforge.io/
11. CAD
1. Fusion360 https://www.autodesk.com/products/fusion-360/overview
2. Vectric VCarve PRO
12. Ergonomics
1. Hot Corners like in Mac OS – winXcorners https://github.com/vhanla/winxcorners
2. WinDynamic Desktop – changing background during day https://github.com/t1m0thyj/WinDynamicDesktop
3. AutoDark Mode https://github.com/AutoDarkMode/Windows-Auto-Night-Mode
4. f.lux https://justgetflux.com/
13. Ad Blocker
1. AdGuard https://adguard.com/
14. System
1. CCleaner https://www.ccleaner.com/
2. HWINFO64
15. VPN
1. Nord VPN
2. OpenVPN
3. VireGuard
16. Communicators
1. Viber
2. MS Teams
3. Skype
4. Slack
17. File Transfer
1. FileZilla
2. Transmission
18. Blue light filter
1. Integrated
2. f.lux
19. Disk analyzer
1. windirstat
Most of these Windows essential apps you can install with one command using Choco. It is much more convenient than going to each website and downloading packages. Just run Power Shell as Administrator terminal and type in:
choco install 7zip, vscode, libreoffice, gimp, inkscape, audacity, teamviewer, ditto, ccleaner, f.lux
After a while of using system you can easily update all your installed via Choco apps using command:
choco upgrade all

## Windows 10 Tweaks

### Remove Cortana
```Get-AppxPackage -allusers Microsoft.549981C3F5F10 | Remove-AppxPackage```

For ADHD remove colours with key combination
crtl win c 

Windows10Debloater