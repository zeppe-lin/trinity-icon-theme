trinity-icon-theme - icon theme adjusted for trinity gtk theme
==============================================================
trinity-icon-theme is free and opensource SVG icon theme, based on
[archdroid-icon-theme](https://github.com/GreenRaccoon23/archdroid-icon-theme)
which in turn is based on Android Lollipop Material Design icons.  The
main difference from archdroid-icon-theme is that color palette have
been adjusted to trinity-gtk-theme and trademark/logo/servicemark
icons have been removed.  Therefore, trinity-icon-theme isn't
prohibited for non-commercial use.


The original sources can be downloaded from:

  1. https://github.com/GreenRaccoon23/archdroid-icon-theme
  2. https://github.com/google/material-design-icons


Preview
-------
![PREVIEW](https://raw.githubusercontent.com/zeppe-lin/trinity-icon-theme/master/preview.png)


Dependencies
------------
- [librsvg 2.40.20+](https://wiki.gnome/org/LibRsvg)
- [hicolor icon theme](https://www.freedesktop.org/wiki/Software/icon-theme)


Install
-------
To install system-wide, copy the content of this directory to
`/usr/share/icons/trinity`, then run the following commands:
```sh
gdk-pixbuf-query-loaders --update-cache
gtk-update-icon-cache -q -t -f /usr/share/icons/trinity
```

To install as user locally, copy the content of this directory to
`~/.themes/trinity`.


License and Copyright
---------------------
Trinity-Icon-Theme the same as archdroid-icon-theme is licensed
through the GNU General Public License v3 or later
<http://gnu.org/licenses/gpl.html>.
Read the LICENSE.GPLv3+ file for copying conditions.

The main source of this package is:

**Material Design Icons, Google.**
Source: https://github.com/google/material-design-icons
Source License:
https://github.com/google/material-design-icons/blob/master/LICENSE

Material Design icons is licensed through the Apache 2.0 License
<https://www.apache.org/licenses/LICENSE-2.0>.
Read the LICENSE.APACHE-2.0 file for copying conditions.

---

Manually designed icons have been inspired by the above source as well
as the following:

---

**Ubuntu-Mono, Canonical Ltd.**
Source: http://packages.ubuntu.com/vivid/ubuntu-mono
Source License:
https://bazaar.launchpad.net/~ubuntu-art-pkg/ubuntu-themes/trunk/view/head:/debian/copyright

Ubuntu-Mono icons is licensed through the CC-BY-SA-3.0 License
<http://creativecommons.org/licenses/by-sa/3.0/>.
Read the LICENSE.CC-BY-SA-3.0 file for copying conditions.


**Mint-X-Icons, Linux Mint (Clement Lefebvre).**
Source: https://github.com/linuxmint/mint-x-icons
Source License:
https://github.com/linuxmint/mint-x-icons/raw/master/debian/copyright

Mint-X-Icons is licensed through the GNU General Public License v3 or
later <http://gnu.org/licenses/gpl.html>.
Read the LICENSE.GPLv3+ file for copying conditions.


**Numix-Icon-Theme, Numix Project.**
Source: https://github.com/numixproject/numix-icon-theme
Source License:
https://github.com/numixproject/numix-icon-theme/blob/master/license

Numix-Icon-Theme is licensed through the GNU General Public License v3
or later <http://gnu.org/licenses/gpl.html>.
Read the LICENSE.GPLv3+ file for copying conditions.


<!-- vim:ft=markdown:sw=2:ts=2:sts=2:et:cc=72:tw=70
End of file. -->