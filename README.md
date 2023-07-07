<!--
# _______  _______  ______  _______  __      
#|       ||   _   ||   __ \|     __||  |.-----.
#|   -  _||       ||      <|__     ||  ||  _  |
#|_______||___|___||___|__||_______||__||   __|
#                                       |__|   
# QARSlp Qtile + Arch Ricing Script
# By: gibranlp <thisdoesnotwork@gibranlp.dev>
# MIT licence
-->

# QARSlp Qtile + Arch Ricing Script

This is a custom theme for the [Qtile](http://www.qtile.org/) window manager that dynamically adapts to the colors generated by [pywal](https://github.com/dylanaraps/pywal). With this theme, you can easily change the appearance of your Qtile environment to match any image or wallpaper using pywal's color extraction and manipulation capabilities.

This config files provide a few minimal and clean look themes, with a focus on simplicity and usability. 

It features a dark & light color schemes with contrasting colors for active and inactive windows, as well as customizable font sizes and styles.

# Features

## Control Panel

I just made a rofi widget with the most common options such as **Set Random Wallpaper**, **Select Wallpaper**, **change the default Backend for  Pywal**, **Move the Bar Top or Bottom**, among others, simply press **Alt + Return** and watch the widget popup.

https://github.com/gibranlp/QARSlp/assets/2806964/3c393d53-eb32-43ae-96aa-b5ac8bbdcf55

## Set Random Wallpaper Theme

To set a random wallpaper simply type Alt + R and the entire system will change with the wallpaper.

https://github.com/gibranlp/QARSlp/assets/2806964/cddb940a-9ada-42a5-8cb7-a23e89cedfaf

## Select Wallpaper 

If you want a specific wallpaper you can use the **Select Wallpaper** widget, or use **mod + shift + E**, and the widget will come up.

![Random Wallpaper](/screenshots/select_wal.gif)

## Different Display Sizes

I use different computers with different monitor sizes, so i managed to make this theme to change to look good on every monitor i have, this theme differenciates between 4K (3840x2160), HD (1920x1080) and a lower resolution (1366 x 768) of a mini laptop.

- 4K (3480 x 2160)
    - ![4K](/screenshots/4k.png)
- HD (1920 x 1080)
    - ![HD](/screenshots/hd.png)
- Lower Resolution (1366 x 768)
    - ![4K](/screenshots/low.png)

## Flexible Bar

With this rofi widget you can change your bar to the top or the bottom, with any theme, just press **mod + shift + W** to bring this widget to the front.

- ![Bar](/screenshots/bars.gif)

## Fonts

The entire system is configures to use the Fira Code Medium font, and Awesome Pro 6 for all the icons in the bar and in the Rofi Widgets.

If you want to change the fonts, make sure you have the fonts installed and then change the lines 29 and 30 in the file ~/.config/qtile/functions.py

```bash
## Fonts
main_font = "Fira Code Medium" # Font in use for the entire system
awesome_font = "Font Awesome 6 Pro" # Font for the icons
```

## Groups Labels

There are Several labels for the groups already defined you can change them by uncommenting the line you want between the lines 476 - 482 in the file ~/.config/qtile/functions.py

```bash
#group_labels=["零","一","二","三","四","五","六","七","八","九"] # Kanji Numbers
#group_labels=["0","1","2","3","4","5","6","7","8","9"] # Numbers
#group_labels=["","","","","","","","","",""] # Circles
#group_labels=["","","","","","","","","",""] # Dot Circles
#group_labels=["󰏃","󰏃","󰏃","󰏃","󰏃","󰏃","󰏃","󰏃","󰏃","󰏃",] # Custom
```

- Kanji Numbers
    - ![wifi](/screenshots/kanji.png)


- Numbers
    - ![wifi](/screenshots/numbers.png)

- Circles
    - ![wifi](/screenshots/circles.png)

- Dot Circles
    - ![wifi](/screenshots/dot-circles.png)

- Custom
    - ![wifi](/screenshots/custom.png)

You can use any icon from [here](https://fontawesome.com/v5/cheatsheet/pro) in case you want to make your own custom groups

# Ethernet & Wifi

## Icon 

The network icon will change automatically depending if you are connectedo the Ethernet or Wifi, when connected to wifi the SSID will also be visible.

- Wifi
    - ![wifi](/screenshots/wifi.png)

- Ethernet
    - ![Ethernet](/screenshots/ethernet.png)

## Net & Wlan Qtile Widgets

In the QARSlp & Slash themes, you can click in the Network icon and the widget will display the current local IP and the Public IP.

- Wifi
    - ![wifi](/screenshots/wifi-ip.png)

- Ethernet
    - ![Ethernet](/screenshots/ethernet-ip.png)

## General Margins and Borders

If you want to change the margins for all themes just go into the lines 57-62 in the file ~/.config/qtile/functions.py

```bash
## Margins
layout_margin=10 # Layout margins
single_layout_margin=10 # Single window margin 
## Borders
layout_border_width=4 # Layout border width
single_border_width=4 # Single border width
```

## Calendar  & Notifications

![Notifications](/screenshots/notifications.gif)


Using Dunst if you click on the clock you will get the current month in the calendar, if you move the mouse wheel on the clock you can change the month upp and down also.

![Calendar](/screenshots/calendar.png)
![Calendar1](/screenshots/calendar1.png)
![Calendar2](/screenshots/calendar2.png)

## Lightdm

This Qtile theme also changes Lightdm with the current wallpaper and color scheme.

![Notifications](/screenshots/lightdm.gif)

![Lightdm1](/screenshots/Lightdm1.png)
![Lightdm2](/screenshots/Lightdm2.png)
![Lightdm3](/screenshots/Lightdm3.png)

# Themes

## Theme Selector

Select the theme you want to use (QARSlp, Slash, Minimal, no_bar), so far, i have in mind a lot more themes.

![Themes](/screenshots/themes.gif)


## QARSlp

![QARSlp1](/screenshots/QARSlp1.png)
![QARSlp2](/screenshots/QARSlp2.png)

## Slash

![Slash1](/screenshots/Slash1.png)
![Slash2](/screenshots/Slash2.png)

# Backends

You can select different backends trough a Rofi widget using the same wallpaper, the backends available are Wal, Colorz, Colorthief and Haishoku.

![Backends](/screenshots/bckends.gif)

## Wal
![Wal1](/screenshots/Wal1.png)
![Wal2](/screenshots/Wal2.png)
## Colorz
![Colorz1](/screenshots/Colorz1.png)
![Colorz2](/screenshots/Colorz2.png)
## Colorthief
![Colorthief1](/screenshots/Colorthierf1.png)
![Colorthief2](/screenshots/Colorthief2.png)
## Haishoku
![Haishoku1](/screenshots/Haishoku1.png)
![Haishoku2](/screenshots/Haishoku2.png)

# Random Colors of the Theme

If you still need more colors all you have to do is to press Alt + Shift + R and this will randomize the current color scheme.

# Rofi Utilities

I have added some [Rofi](https://github.com/davatorium/rofi) utilities, to make life simpler, here they are:

## Launcher

![Launcher](/screenshots/launcher.gif)

Launch any application or search for files and folders

![Launcher](/screenshots/Launcher.png)

## QARSlp Shortcuts

Check out all the shortcuts of the system

![Shortcuts](/screenshots/screenshot.gif)

![Shortcuts](/screenshots/Shortcuts.png)


## Multi Monitor Management

Manage multi monitors fast and easy, select your main monitor and resolution, and then select where to put the sencodary monitor (left, right, up, down)

![Multi Monitor](/screenshots/Multi_monitor.png)

## Color Picker

Select Hex or RGB and you can then click on the screen to get the color using [Farge](https://github.com/sdushantha/farge), you will get the color via notification using [Dunst](https://github.com/dunst-project/dunst)

![Color Picker](/screenshots/color_picker.gif)

![Color Picker1](/screenshots/Color_picker1.png)
![Color Picker1](/screenshots/Color_picker2.png)

## Wifi Menu

Select and connect to Wifi using Rofi.

![Wifi](/screenshots/Wifi.png)

## Sesion Menu

Lock the PC, Sign out, Reboot or Poweroff.

![Session](/screenshots/Session.png)

## Screenshot Widget

Take Screenshots of the Screen, an Area, a Window, or the Screen in 5 seconds using [Scrot](https://github.com/dreamer/scrot) and [Flameshot](https://flameshot.org/)

![Screenshot](/screenshots/screenshot.gif)

![Screenshot](/screenshots/Screenshot.png)

## Night Light

Change the temperature of the monitor using [Redshift](https://github.com/jonls/redshift)

![nightLight](/screenshots/nightlight.gif)

![Night Light](/screenshots/Night_light.png)

## Conclusion
With QARSlp you can have an always riced system, ready for productivity and fun, its compatible  and the ricing also covers applications like VScode, Telegram, Chrome, Brave, all GTk and CLI apps.

# Installation

To install QARSlp you will need to install a few dependencies:

## Pacman

```bash
feh base-devel alsa-utils pulseaudio-alsa pavucontrol openssh alacritty xcolor playerctl scrot rofi surfraw python-pip ranger lxappearance bmon acpilight lm_sensors nm-connection-editor arandr python-psutil python-xdg python-iwlib python-dateutil ueberzug xsettingsd zsh dunst tk lightdm-gtk-greeter-settings reflector rsync curl bc neofetch xorg-xkill xdg-user-dirs bluez bluez-tools blueman htop networkmanager noto-fonts noto-fonts-cjk libayatana-appindicator  tumbler redshift libmicrodns protobuf xorg-xdpyinfo
```
## AUR

QARSlp works with the Qtile-git and qtile-extras-git versions among other packages

```bash
qtile-git farge qtile-extras-git wpgtk-git cava i3lock-color picom-tyrone-git
```

## Pip

You also need to install these pip packages

```bash
requests cairocffi xcffib fontawesome ipc colorz colorthief haishoku dbus-next git+http://github.com/bcbnz/python-rofi.git
```

If you want to use ZSH run this commands to install Oh-My-Zsh

```bash
h -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)" "" --unattended
git clone https://github.com/zsh-users/zsh-autosuggestions.git ~/.oh-my-zsh/plugins/zsh-autosuggestions
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ~/.oh-my-zsh/plugins/zsh-syntax-highlighting
```

Once all the dependencies are installed, you must generate the templates for GTK by runing:

```bash
wpg-install.sh -gio
```

Then run the copy_files.sh script to generate all the folders and copy all the necesary files.

Finally in a terminal run:

```bash
genwal
```
This will generate the first palette of colors and set the wallpaper, the path of the wallpaper is ~/Pictures/Wallpapers, just put all your wallpapers inside and enjoy.

# Next Steps

- [ ] I will be working in the light themes which now look bad in general.
- [ ] Generate an AUR Installation package
- [ ] Add more themes (if you have suggestions add them in issues)

If you like it please help me support this project, some coffee would help me to improve it and dedicate more time. thanks.

<a href="https://www.patreon.com/user?u=48005915"><img src="/screenshots/patreon.svg" width=50></a>
<a href="https://www.buymeacoffee.com/gibranlp"><img src="https://img.buymeacoffee.com/button-api/?text=Buy me a Coffee&emoji=&slug=gibranlp&button_colour=FFDD00&font_colour=000000&font_family=Bree&outline_colour=000000&coffee_colour=ffffff"></a>
