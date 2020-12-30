# dotfiles.arm64
dotfiles for my arm64 SBCs
## use this command to clone
git clone --bare https://github.com/saewoonam/dotfiles.arm64.git $HOME/.cfg
## add this to end of .bashrc
alias config='/usr/bin/git --git-dir=$HOME/.cfg/ --work-tree=$HOME'
