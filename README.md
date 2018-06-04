# HomeBridge Nest for RHEL

This is a project based upon the galaxy role for installing 
homebridge on Ubuntu. Knocked up in an afternoon and uploaded to github for 
safe keeping.

I should probably turn this into a role all by itself.

# Purpose
The Nest thermostat does not have support for Apple Homekit and we 
are a fanboys (and girls). I wanted to be able to ask Siri to set the temperature
of my house and boost the hotwater.

Unfortunately boosting the hotwater is currently not supported by the
Nest API and seems to be only a UK thing.

# Notes
The secrets.yml file is vaulted. The variables encrypted inside are used in the 
config.json template.

This is mostly based on [https://galaxy.ansible.com/wrboyce/homebridge/]
Modified for RHEL 7.5 by using geerlingguy roles.

Information about the homebridge-nest plugin can be found here
[https://github.com/chrisjshull/homebridge-nest] Follow the instructions in the 
Readme.md to understand what should be put into the configuration file.