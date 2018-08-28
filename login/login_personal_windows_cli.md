# Command line - personal Windows

To connect from a personal Windows machine to the GeoSciences Linux server you can use PuTTY. PuTTY is a free and open source program that provides a command line interface to allow you to connect remotely to other machines over a network. You can download PuTTY from [here](https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html).

First, make sure you are connected to the University VPN service \([more information can be found here](http://www.ed.ac.uk/information-services/computing/desktop-personal/vpn)\).

Then, open PuTTY and configure the PuTTY session using the instructions below. `burn` is the name of the GeoSciences Linux server, it's address is `burn.geos.ed.ac.uk`:

* "Host Name \(or IP address\)" = `burn.geos.ed.ac.uk`
* "Port" = `22`
* "Connection type:" = `SSH`
* In "Category: Connection, SSH" Check `Enable X11 forwarding` - which allows X window applications to be opened on your desktop \(e.g. `xeyes`, see "Managing Processes -&gt; Background Processes"\)

Then click "Open" to start the connection, type your UUN \(e.g. `s1234567`\) and the password you use to login to MyEd, University Windows machines etc.

