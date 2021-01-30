# nouveGnomeGray
GNOME icon theme

# GNOME icon theme Installation:

![ScreenShot](screenshot.jpg "nouveGnomeGray")

(1) Put this (extracted) folder in ~/.local/share/icons/ (create the last folder "icons" if it doesn't exist; here ~ is your home);

(2) In GNOME3, you could update the icon cache with the following command in Terminal:

`gtk-update-icon-cache-3.0 ~/.icons/nouveGnomeGray`

(3) In GNOME3, choose the theme from Advanced Settings > Theme > Icon Theme.

This is true for Debian-based systems, at least. Distros:

By default, the theme uses the GNOME foot logo as the distro logo. To make the theme use the logo of your distro (in start menu, for example), find "YOUR_DISTRO-logo.png" in the 16x16 to 48x48 "places" folders and link these images to it:

distributor-logo.png start-here.png gnome-main-menu.png

For example, open a terminal in the 16x16 "places" folder and do:

`ln -s -f YOUR_DISTRO-logo.png distributor-logo.png`

# Additionally, a ready-made package for Arch Linux was added.
