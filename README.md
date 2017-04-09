## Numix
This is a fork of the [Numix GTK theme](https://github.com/numixproject/numix-gtk-theme) which uses the Solarized colour scheme.

## Build It

First, you need to compile the theme using the [Sass](http://sass-lang.com/) compiler.

To install Sass, install Ruby and the gem command using your distribution's package manager. Then install `sass` with the `gem` command.

`gem install sass`

You'll also need the ```glib-compile-schemas``` and  ```gdk-pixbuf-pixdata``` commands in your path to generate the gresource binary. Install them using your distribution's package manager. After installing all the dependencies, change to the cloned directory and, run the following in Terminal.

`sudo make install`

