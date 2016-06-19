# PlexSleep

A simple script to allow you to suspend your Linix PC/Server if there is an no activity from a Plex Media Server after a set amount of time (default 60 mins).


Please open PlexSleep.conf in your text editor and make sure your system settings are correct (IP address, port, desired time of inactivity, etc)

This script needs Python3 in order to work. Please make sure this is installed before you proceed. 

To install: Copy PlexSleep.conf to /etc/init/ folder (make sure it is exectuable)

To run: This will run the PlexSleep service on startup. To manually run open terminal and enter "sudo service PlexSleep start" or "sudo service PlexSleep stop" depending on your need. 

