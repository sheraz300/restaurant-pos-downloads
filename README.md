# Maahi POS downloads

Public Windows and Mac development builds for Maahi Restaurant POS.
The application source is maintained in a separate private repository.

## Download

- [Windows installer (.exe)](https://github.com/sheraz300/restaurant-pos-downloads/releases/latest/download/Maahi-POS-Setup.exe)
- [Portable Windows ZIP](https://github.com/sheraz300/restaurant-pos-downloads/releases/latest/download/Maahi-Windows-Portable.zip)
- [Intel Mac app ZIP](https://github.com/sheraz300/restaurant-pos-downloads/releases/latest/download/Maahi-Mac-Intel.zip)
- [All release files and SHA-256 checksums](https://github.com/sheraz300/restaurant-pos-downloads/releases/latest)

Links become active after the first successful pipeline publication and always
point to the latest successfully published build. Previous versions remain under
[Releases](https://github.com/sheraz300/restaurant-pos-downloads/releases).

## Windows

Open `Maahi-POS-Setup.exe`. The installer includes the .NET runtime and supporting
files, installs for the current Windows user and creates a Start menu shortcut.
Uninstall through Windows Settings → Apps. Windows 10/11 x64 is required.

For the portable version, extract the whole ZIP and run `Maahi.Desktop.exe`.
Keep all files in that folder together. The separate Server ZIP is for developer
setup; PostgreSQL is not bundled in the desktop installer.

## Current status

**Development UI prototype.** The desktop currently uses sample data. Live
restaurant/warehouse backend binding and the separate HR portal are still pending.
Use this build for demonstrations, not real restaurant billing.

These are unsigned development packages. Automated checks cover database/API
behavior, Windows installation/rendering/uninstallation and Intel Mac rendering.
They do not replace real printer, fiscal-invoicing or operational acceptance tests.

Each release includes build metadata and checksums. The private application's
source code, credentials and database records are not published in this repo.
