---
title: Things to do after installing Arch Linux
date: 2023-03-25
description: 
type: page
draft: true
---

This article has not been completed. You can come again after some time.



`lsblk`

`umount /mnt`

`shutdown now`


bspwm config - `.config/bspwm/bspwmrc`

sxhkd config - `.config/sxhkd/sxhkdrc

`mkdir code dl docs music pics vids`




For unlimited bash history


`cat ~/.bash_history >>~/.bash_eternal_history`

``` bash
# Eternal bash history.
# ---------------------
# Undocumented feature which sets the size to "unlimited".
# http://stackoverflow.com/questions/9457233/unlimited-bash-history
export HISTFILESIZE=-1
export HISTSIZE=-1
export HISTTIMEFORMAT="[%F %T] "
# Change the file location because certain bash sessions truncate .bash_history file upon close.
# http://superuser.com/questions/575479/bash-history-truncated-to-500-lines-on-each-login
export HISTFILE=~/.bash_eternal_history
# Force prompt to write history after every command.
# http://superuser.com/questions/20900/bash-history-loss
PROMPT_COMMAND="history -a; $PROMPT_COMMAND"
```
            
            
Flatpak apps - 
``` bash
flatpak install \
flathub com.github.Eloston.UngoogledChromium \
flathub com.transmissionbt.Transmission \
flathub org.telegram.desktop \
```
            
            

  
