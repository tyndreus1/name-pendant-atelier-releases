# Name Pendant Atelier — releases

This repository contains only the **Windows program releases** of Name Pendant Atelier (a name-pendant / necklace design tool for laser cutting). There is no source code here.

## Download and install

1. Open the [latest release](https://github.com/tyndreus1/name-pendant-atelier-releases/releases/latest) and download `NamePendantAtelier-vNN-win64.zip`.
2. Optional: check the file against `NamePendantAtelier-vNN-win64.zip.sha256`
   (PowerShell: `Get-FileHash .\NamePendantAtelier-vNN-win64.zip -Algorithm SHA256`).
3. Unzip it into a folder of your choice, for example `Desktop\Name Pendant Atelier`.
4. Start `NamePendantAtelier.exe`. No Python installation is needed.

## Updates

The program checks this repository for a newer release, shows what's new and installs only after you agree. It verifies the download with SHA-256, backs up the current program into the `updates` folder first, and keeps your settings, projects and the `fonts` folder.

## Fonts

Put licensed `.ttf` / `.otf` files into the program's `fonts` folder; they appear first in the font list. No fonts are distributed here.
