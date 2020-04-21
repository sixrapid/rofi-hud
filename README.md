# rofi-hud

rofi-hud is a HUD-menu script for [rofi](https://github.com/davatorium/rofi). It was adapted from [plasma-hud](https://github.com/Zren/plasma-hud) and [HUD.py](https://gist.github.com/snippins/ee943f2b25db555ef12107f7cee20241). It currently supports applications with dbus or org.gtk.Menus interface support.

## Dependencies
Tested with rofi 1.5.4 and python 3.8.2. Other dependencies include python-dbus, python-xlib, gobject-introspection and appmenu-gtk-module (and possibly some others).

## Usage
Bind "python rofi-hud.py" to your preferred keybinding. Use keybinding while a supported type of window is focused.

rofi-hud uses your default rofi configuration. Theming etc. is hence done via .config/rofi/config.rasi, or whatever you are using to configure rofi.

## License
Licensed under GPL 2.0.
