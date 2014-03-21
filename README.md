.irssi
======

This is my configuration for Irssi, the client of the future:
http://www.irssi.org/

To use it, clone the repository to your home directory:

```sh
git clone https://github.com/ncortot/dot-irssi.git ~/.irssi
```

Create a new configuration file:

```sh
cp ~/.irssi/config.template ~/.irssi/config
```

Then edit `~/.irssi/config` to your needs. Important settings that you should
change are marked with `# TODO`.


The nicklist plugin does not work with screen unless you run two screen
sessions, one inside another. To start Irssi for the first time, type:

```sh
screen -US irc
screen -US irssi
irssi
```

Then to disconnect from the outer screen, type `Control-A d`.

To connect back to your screen and Irssi, type:

```sh
screen -Udr irc
```

More documentation can be found on:
  - [The Irssi Startup HOWTO](http://www.irssi.org/documentation/startup)
  - [A Guide to Efficiently Using Irssi and Screen](http://quadpoint.org/articles/irssi/)

