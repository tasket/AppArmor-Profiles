# AppArmor-Profiles

Although AppArmor is a great idea to enhance security, publishers like Mozilla and Canonical have either not taken an interest or done a poor job of maintaining profiles. So I will be adding (hopefully better-functioning) profiles here, starting with Firefox.

To install a profile on your system, copy it to your /etc/apparmor.d folder and run `sudo aa-enforce <profile path>`. (You will need to have AppArmor already enabled for your VMs...)

----
## See Also:

[Whonix - Enabling AppArmor](https://www.whonix.org/wiki/AppArmor)
