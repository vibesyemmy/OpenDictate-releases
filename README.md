# Open Dictate downloads

Talk instead of type, on your Mac. Press a shortcut, speak, and your words are typed into whatever app you're using. Speech is turned into text on your Mac by default.

This repository only hosts the app's downloads. There is no source code here.

## Download

Get the latest `.dmg` from **[Releases](https://github.com/vibesyemmy/OpenDictate-releases/releases/latest)**, open it, and drag **Open Dictate** to **Applications**. The app is signed and notarized by Apple, and its setup guide walks you through the rest.

- Requires a Mac with Apple Silicon and macOS 11 or later.
- Recording meetings needs macOS 14.2 or later.

Open Dictate checks this page once a day for new versions and tells you on its Home screen when one is out. You can turn that off in **Settings › About**.

## Checking a download

Each release lists the SHA-256 checksum of its DMG. To check yours:

```bash
shasum -a 256 ~/Downloads/Open-Dictate-*.dmg
```
