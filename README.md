[![Snap Status](https://build.snapcraft.io/badge/ogra1/extract-deb-snap.svg)](https://build.snapcraft.io/user/ogra1/extract-deb-snap)

# extract-deb-snap
Snap package to extract .deb files in your home dir.

A simple wrapper to dpkg -x to extract .deb packages in a subdirectory of your home.
This is a helpful tool in case you want to access binary .deb content on an UbuntuCore system.

Note that you need to connect the home interface first when using this
tool on an UbuntuCore system with the command

snap connect extract-deb:home

# usage
extract-deb /path/to/debian/package outputdir
