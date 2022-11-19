# CYBIT

THIS CONFIG WAS TESTED AND BUILT IN **MANJARO LINUX** and **AWESOMEWM**

You will need:
- **CONKY** (Desktop widgets)
- **AWESOMEWM** (Window Manager)
- **TERMINESS NERD FONTS**

# SETUP
The awesomewm code changes the wallpaper for each workspace, so you need to copy the files in homefolder/Pictures/Wallpapers/ to your ~/Pictures/Wallpapers/ folder, you can change the wallpapers but the name of each wallpaper name must be the number corresponding to the workspace to which you assign it (for workspace 1: 1.png)

- Copy the files in homefolder/config/ to your ~/.config folder
- Copy the files in bin/ to your binaries path (usually /usr/bin/)

- Edit ~/.config/awesome/rc.lua
- Go to line 51 if you want to change the default terminal
- Go to line 56, there's the screens config. Change it to yours
- Go to line 413 and change the path to the Wallpapers folder

- Now, if you have a secondary disk, edit the ~/.config/conky/left.conf and change the sdisk var to your disk path

It's done

# SCREENSHOTS
![alt text](https://raw.githubusercontent.com/v1ewport/CYBIT/main/screenshots.png)
