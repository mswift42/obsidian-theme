obsidian-theme
==============

port of the Eclipse theme Obsidian

![Screenshot](https://github.com/mswift42/obsidian-theme/raw/master/Screenshot.png)

Available on Melpa.

Installation Instructions
-------------------------

add the following lines to your init.el (only if you have not done so already):

    (setq package-archives '(("gnu" . "http://elpa.gnu.org/packages/")
                             ("marmalade" . "http://marmalade-repo.org/packages/")
                             ("melpa" . "http://melpa.milkbox.net/packages/")))

    (package-initialize)



This will add the gnu, marmalade and melpa repos to your emacs setup.

To install the theme

**M-x package-install** obsidian-theme


To use the obsidian theme when starting emacs add this to your init.el:

    (load-theme 'obsidian)


Credits
-------

This is a port of the [obsidian theme](http://eclipsecolorthemes.org/?view=theme&id=21) for Eclipse by Morinar.


