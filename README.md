## Darkflip
Darkflip is a wrapper of useful `gsettings` commands, offering a GNOME Tweaks-like functionality on Debian-based mobile distros running the [Phosh](https://en.wikipedia.org/wiki/Phosh) desktop environment. It depends on the `yad` and `bc` packages.

### Installation
See the [releases](https://github.com/thomashastings/darkflip/releases) for a downloadable `*.deb` package.
It can be installed by running `sudo apt install ./darkflip.deb`

You can also use the repository to build it locally:
```
git clone https://github.com/thomashastings/darkflip.git
cd darkflip
dpkg-deb --build darkflip/
sudo apt install ./darkflip.deb
```

![Screenshot](https://raw.githubusercontent.com/thomashastings/darkflip/c00ee562f9653f7969c566a8eedb8be0dd515c9d/screenshots/darkflip_screenshot.png)

### Features
- Easily switch between the Adwaita Light and Adwaita Dark default themes (hence the name Darkflip)
- Change clock settings (top bar and lock screen)
- Change font scaling
- Allow volume above 100%
- Toggle event sounds
- Toggle animations
- Toggle notification banners and notifications on the lock screen
- Disable microphone, camera, sound output

Note: Features marked with `(?)` may not work, or might cause freezing. Use with caution.

### Credit
The icon is based on the icon for `GNOME Tweaks` in the [Adwaita Icon Theme](https://github.com/GNOME/adwaita-icon-theme]), taken under the Creative Commons Attribution-Share Alike 3.0 license.

### License
This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License version 3, as published by the Free Software Foundation.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranties of MERCHANTABILITY, SATISFACTORY QUALITY, or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program. If not, see http://www.gnu.org/licenses/.
