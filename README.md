# GFreenect
GFreenect is a wrapper for the Freenect library written using Glib in order to control a Kinect device and make it easy to use with GNOME technologies.

# Install

### Ubuntu 16.04.2 LTS

#### Install [libfreenect](https://github.com/OpenKinect/libfreenect)

#### clone repo

`cd GFreenect/`

`sudo apt-get install gtk-doc-tools autoconf libgirepository1.0-dev gobject-introspection`

`./autogen.sh`

`make`

`sudo make install`
