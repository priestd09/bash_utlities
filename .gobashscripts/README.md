#README golang auto install

`Script By: Gentry Rolofson`

Fully automatic golang install script for mac OSX, LINUX and FreeBSD.

Script will check for os version automatically and check for current version of golang, it will check if you have

golang installed, if you do it willl check if its the most current version if it isnt the most current version it will install the mot current version

To run this script properly all you need to do is cd into the location of the installgo.sh file and type into terminal

`. installgo.sh`

From there you can follow the onscreen instructions, this will give the option to install homebrew for mac OSX << a very good package manager think apt-get

It will then install wget this is also an essential terminal tool.

This tool will also place your goworkspace in the proper location with your git username, and automatically setup your go environment variables, setting them inside your `.bash_profile`

###Dependencies

NONE CURL will now do everything!

- [ ] Homebrew
- [ ] wget

###Awesome Addons!!

These are great, the homebrew is as close to apt-get as mac osx can get!

http://brew.sh/

- [x] Homebrew
- [x] wget
