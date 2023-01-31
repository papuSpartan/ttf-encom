# ttf-encom
Patched encom font

This is the (actual) font that is used in Tron: Legacy (so not TR2N):
![2023-01-31_07-42](https://user-images.githubusercontent.com/30642826/215776488-20acfcb9-0805-48ef-a09f-dc9f9754297b.png)

The font is sourced from an archived version of http://disneydigitalbooks.go.com/tron. leveraging the 
waybackmachine at [this url](https://web.archive.org/web/20120708193507/http://disneydigitalbooks.go.com/tron/).


It has been patched such that the missing lowercase characters simply mirror the existing capital ones.
This allows for easy use with applications such as [polybar](https://github.com/polybar/polybar).

## Installation
I made [an AUR package for installing this font](https://aur.archlinux.org/packages/ttf-encom) which can be installed on arch based linux distributions.\
Ex. of installing with yay package manager
```
yay -S ttf-encom
```

If you are using another OS like windows, you should be able to use the builtin font manager to easily install it.
