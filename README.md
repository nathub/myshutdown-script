My current implementation simply puts this "myshutdown" file in "/usr/bin/" so I can call it in the terminal.
It can be called with sudo or it can be called and prompt you for your sudo password.

This has only been tested in Gentoo Linux. I'm not sure by what mechanism the sudo privileges are passed through, or if that will break on other setups.
