# myde
## Base System
Ubunutu Minimal 16.04 (mini.iso)
* `sudo apt install software-properties-common build-essential`
* install Xorg `sudo apt install xorg`

## Desktop Manager
Lightdm: `sudo apt install lightdm lightdm-gtk-greeter lightdm-gtk-greeter-settings`

## Window Manager
Openbox: `sudo apt install openbox` (checked)
* install gksu `sudo apt install gksu`
* edit autostart applications by create `~/.config/openbox/autostart.sh` and execute the program to start

## Desktop Overview
Skippy-XD: `sudo add-apt-repository ppa:landronimirc/skippy-xd-daily && sudo apt update && sudo apt install skippy-xd`

## Application Launcher
obmenu: `sudo apt install menu obmenu`
Synapse: `sudo apt install synapse` (checked)
autostart line: `synapse -s &` 

## Dock
Plank: `sudo apt install plank` (checked)

## Panel
Tint2: `sudo apt install tint2` (checked)

## Composite Manager
xcompmgr: `sudo apt install xcompmgr` (checked)

## Wallpaper Manager
nitrogen: `sudo apt install nitrogen` (checked)
autostart line: `nitrogen --restore &`

## Monitor configuration
`xrandr --output HDMI1 --mode 1920x1080 --right-of VGA1`
`xrandr --output HDMI1 --primary`

## Theming Manager
LXAppearance: `sudo apt install lxappearance`
## File Manager
Nemo: `sudo apt install nemo` (checked)
Thunar: `sudo apt install thunar`

## zsh and prezto

## terminal emulator
Terminator: `sudo apt install terminator`
