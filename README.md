# pkgsync
A simple script to sync installed packages across Arch installs

# Usage
Configure pkgsync by modifying /etc/default/pkgsync, follow instructions in comments.  Then just run pkgsync on each system to sync packages.

# Dependencies
This script is only for Linux distros that use pacman for package management.  All dependencies are included in the Arch Linux base group but are listed out here for general info:

Executable | Arch package providing
--- | ---
bash | bash
xargs | findutils
pacman | pacman
comm | coreutils
sort | coreutils

## Links
AUR Package: https://aur.archlinux.org/packages/pkgsync
