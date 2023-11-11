# x-xcursor-thumbnailer
Two files for previewing Linux cursors in file manager.

![](screenshot.png)

Now it uses GD gawk library, if you can install packages from Arch User Repository, you can get easy installation of it. Later the ImageMagick will be an only dependency.

Dependencies: `gawk`, `imagemagick`, `gawk-gd`, `xcur2png`

I want to remove `gawk-gd` dependency later.

Installation:
Clone:
```
git clone https://github.com/nestoris/x-xcursor-thumbnailer.git && cd x-xcursor-thumbnailer
```

Copy:
```
sudo cp xmcthumbnailer /usr/lib/
sudo cp xcursor.thumbnailer /usr/share/thumbnailers/
```

Maybe you'll need a reboot after it.