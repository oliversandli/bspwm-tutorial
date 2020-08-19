# bspwm-tutorial
---
An edited and formatted bspwm tutorial based on https://classicforum.manjaro.org/index.php?topic=18970.0

I found this awesome (not to be confused with [awesome](https://github.com/awesomeWM/awesome)) tutorial by *Chrysostomus* on setting up [bspwm](https://github.com/baskerville/bspwm) and wanted to store it in a more permanent spot than a forum thread. Note that it was originally written in December 2014, so if you find any outdated information please submit an issue (see . Enjoy!

---

## TOC

- [What Is It?](#what-is-it?)
- [Features](#features)
- [Who Should Use bspwm?](#who-should-use-bspwm?)

## What Is It?

*bspwm* (binary space partitioning window manager) is fairly young window manager, and in active development. Like *openbox*, it can be used with desktop environment like *xfce* or *lxqt*, or on its own. It is particularly suited for people who don't have workflow set in stone.

It may not be the lightest nor the most stable window manager out there, but it makes up for it with ease of use and powerful features. That is not to say that it is heavy or unstable. I think it is lighter than *openbox*, just not as tiny and minimalistic as *dwm* or *monsterwm* or as unshakable as *xmonad*.

*bspwm* is easy to configure, but tricky to setup if you don't know what you are doing. To remedy this, I wrote this little guide to help.

## Features

Watch this screencast to understand: https://github.com/windelicato/dotfiles/blob/master/why_bspwm.gif

*bspwm* is easy to configure, but tricky to setup if you don't know what you are doing. To remedy this, I (Chrysostomus) wrote this little guide to help. Like *herbstluftwm*, *bspwm* is driven with terminal commands that can be bound to hotkeys. Also like *herbstluftwm*, the configuration file is just an autostart file that runs commands for setting rules.

*bspwm* is a tiling window manager like *dwm*, *awesome*, *i3* or *xmonad*. This means that windows do not usually overlap with each other. Instead, all the available space on screen is automatically divided between them. This saves time and ensures that screen real estate is used efficiently. *bspwm* can also float windows. Unlike *dwm* or *xmonad*, you can move windows with mouse without making them floating. Unlike *awesome wm*, you can have tiled and floating windows in same workspace. Otherwise mouse controls are quite close to *awesome wm*.

*bspwm* features a combination of automatic tiling (like *awesome*, *dwm* and *xmonad*) and manual tiling (like *herbstluftwm*, *musca* and *i3*). When you open a new window, one of the existing windows is divided in half (or whatever splitting ratio you have set) to make room for the new window. There are no predefined layouts. Open more windows, and they form a spiral. However, you can manually choose where the new window is created, or split existing window and move another window to the split.

Tiling window managers require you to use workspaces or tags actively, since everything is usually visible and not minimized. Moving things between them is usually easier than in most stacking window managers. You can add and delete workspaces and give them names. You can also make windows 'sticky', which means they are visible in all workspaces.

*bspwm* also has option to have gaps between the windows, which can be adjusted on the fly. It also has pseudo-floating windows, which are placed like tiling windows, but can have any size.

## Who Should Use bspwm?

Many tiling window manager users like to have very specific workflow. The browser always goes to the "web" workspace and so on. While this is also possible with *bspwm*, its combination of manual and automatic tiling make it suited for an unplanned or irregular workflow. Windows just go to a reasonable place, and adjusting things is intuitive.

- Tiling wms are good match for small screens, because all screen real estate is used efficiently and managing maximized windows is simple.
- They are also suited for big screens, because they save time you would otherwise use moving windows around.
- In particular *bspwm* is suited for people who like tweak and tinker with stuff. You won't be getting an out of the box experience, but you'll be making things work just the way you like them.
- Also, it is quite light. It works very smoothly even on older hardware, and won't cause suicidal feelings if you run it on a Raspberry Pi. I think.
