#install zsh

pacman -S zsh

#install oh my zsh
clone this repositories and cd into the dir
./install.sh

#oh my zsh theme
<https://github.com/ohmyzsh/ohmyzsh/wiki/Themes> 
suggest agnoster

#change default shell

chsh -s /bin/zsh

#default config

cp /usr/share/oh-my-zsh/zshrc ~/.zshrc

#change theme

edit ~/.zshrc 

find ZSH_THEME="robbyrussell" 

change to 

ZSH_THEME="agnoster"
