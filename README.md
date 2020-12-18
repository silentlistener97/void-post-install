# Void Linux Post Installtion Script for DWM

This is a simple bash sript for an easy post installation process of Void Linux.

## What it does ?
1. Update the system.
2. Enabling non-free repositories.
3. Create user directories.
4. Configure network with Newtwork Manager.
5. Configure audio.
6. Install intel graphics drivers with xorg-minimal installation.
7. Install dejavu-fonts-ttf.
8. Install some packages essentiol for compiling packages.
9. Installed untouched virsion of DWM, St terminal and DMenu.
10. Install libxft-bgra to get color emoji support and install noto-fonts-emoji.
11. Configure TLP.

## How to run ?
1. Boot into Void Linux and sign in as user(Not as root).
2. Connect to the internet and install git first
```bash
sudo xbps-install -S git
```
3. Clone the repository and run install
```bash
git clone https://github.com/silentlistener97/void-post-install
cd void-post-install
chmod +x install
./install
```
### Optional
You can install some packagesj if you like. Just edit the script as your likings.
