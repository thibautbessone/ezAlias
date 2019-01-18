# ezAlias

## Excuse me, what is that ?

It is a simple way to manage aliases in the Windows terminal. It was originally meant to use common commands from Linux on Windows (`ls` > `dir`), but it can be used to easily manage aliases on Windows.

## Seems OK, how do I install this ?

* Download the `scripts` folder
* Put it in your User folder (typically `C:\Users\%USERNAME%\`)
* Execute `loader.cmd`
* That's it 

## It's installed, how do I use it ?

* Open `cmd_aliases.txt` with any text editor
* Your aliases has to follow this syntax : `yourAlias=command [$*]`. The `$*` is used to allow parameters to aliased commands.
* Restart your computer. Your newly created aliases should be available.

[Reference for common commands in Windows & Linux](http://www.yolinux.com/TUTORIALS/unix_for_dos_users.html)