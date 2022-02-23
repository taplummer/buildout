# Turn Me Red

This is a pretty straight-forward script that will install various packages onto your Debian-based machine to convert you from a Script Kiddie to a Prepared Script Kiddie. (chuckle)

It needs to be run with ```sudo``` privs because we're going to be installing packages, creating commands, and so on.

The purpose of this script is to avoid that situation where you upgrade to a new machine and have to manually download each and every tool... 

This will also download my Citadel scanner and make it a command on your machine, so instead of needing to be in a specific directory, you can simply type ```sudo citadel <target>``` and it'll work. Keep in mind that this will not retain the docker/vagrant functionality included in the Citadel repo. It will run on your host. 

## Installation Instructions

```git clone https://github.com/taplummer/buildout.git```

```cd buildout```

```sudo ./TurnMeRed```
