# KDE in Qubes
KDE can be installed very simply:  
`sudo qubes-dom0-update @kde-desktop-qubes`

Log out, you can then choose Plasma and log in.

## Virtual Desktops
The system starts with a single desktop.  
You can add more desktops by Right Clicking on the desktop icon and selecting "Add Virtual desktop".  
![Adding a desktop](Images/desktops.png)

You can move windows between desktops by dragging the outlines on the desktop icon.  
KDE has excellent support for keyboard shortcuts - You can move between desktops, and move windows between desktops, using the keyboard.
The default shortcuts are `Ctrl+F1` to switch to desktop 1....  , and you can add custom shortcuts for other actions.

If you have many windows open for the same qube, KDE will nest them under a single button.
kde1 - if you hover over, you will see a thumbnail.  
![Hovering over windows](Images/kde1.png)
If you click, a list of the windows.  
![Listing windows](Images/kde2.png)

All of this is fairly standard stuff.
You can Alt+Tab to get a list of open windows, and cycle through them.
![Listing open windows with Alt+Tab](Images/kde3.png)

And you can filter this to apply to only the current desktop, or all desktops.
Again, pretty standard.
You can hit the top left corner of the screen to see thumbnails of all open windows, or `Ctrl+<F9>` - then you can jump to the window you want.

## Taming the menu
Xfce has a horrible menu system.
Even a simple Qubes install has a menu that is overblown and difficult to work with.  
![Example Xfce menu](Images/xfce_menu.png)
KDE has a number of different menu widgets - a full screen dashboard, a launcher
![KDE launcher](Images/kde_menu.png)
, or a more traditional menu.
![KDE menu](Images/kde_menu2.png)
The LeftHand side contains Favourites - the top icon is for KDE settings, useful for setting custom keyboard shortcuts and window controls.

KDE has a menu editor - Right click on the Menu Icon and select "Edit Applications".
![getting to the menu editor](Images/kde_menu3.png)
You can create sub-menus, and move items by drag and drop.
![menu editor](Images/kde_menu4.png)

You can customise the menu as much as you like.
Perhaps grouping qubes together, and creating a submenu for Templates.
![menu editor with Grouped qubes](Images/kde_menu5.png)
Or even putting the emphasis on applications:
![menu editor with Grouped qubes](Images/kde_menu6.png)
Or simplified further:
![menu editor with Grouped qubes simplified](Images/kde_menu7.png)
Notice that here some of the applications are listed without any reference to the qubes that provide them.

You can also customise Favourites - Right click on any entry, and select "Add to Favourites"
![Adding applications to the Favourites list](Images/kde_menu8.png)

Of course, you can also add short cuts to the desktop. Just Right click on any entry, and select "Add to Desktop"

