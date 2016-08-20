ABOUT:
minimus Window Manager

A highly configurable and manageable tiling Window Manager forked from WMFS.

- Moist von Lipwig <https://moistvl.github.io>
LICENSE: BSD

ORIGINAL WMFS1 AUTHORS : (in order of commits and > 5 commits)
 - Martin Duquesnoy <xorg62@gmail.com>
 - Philippe Pepiot <phil@philpep.org>
 - Marc Lagrange <markocpc@gmail.com>
 - OldMan <tele-post@mail.ru>
 - Raphael Khaiat <raphael@khaiat.org>
 - Tomáš Chvátal <scarabeus@gentoo.org>
 - David Delassus <linkdd@ydb.me>

REQUIREMENT :
  - freetype2
  - libxft
  - libx11
  - libxinerama (optional)
  - libxrandr   (optional)
  - imlib2      (optional)

OS :
  - GNU/Linux : Supported.
  - FreeBSD/OpenBSD/NetBSD : Supported.
  - Windows 2000/XP/Vista/7/8 : Supported via Cygwin

INSTALL :

./configure [--without-imlib2|--without-xrandr|--without-xinerama] (./configure -h)
('./configure --prefix /usr --xdg-config-dir /etc/xdg' is a sane and easy default)
make
sudo make install

OPERATING SYSTEMS :
  - MWM is available for GNU+Linux on GitHub
  - MWM has been tested and works under CygWin on Windows.



