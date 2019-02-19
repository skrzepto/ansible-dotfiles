# Ansible Dotfiles

Make sure current user is in the sudoer file,
to make life easier generate ssh key and add it to git before running script

```
sudo yum install ansible git
git clone git@github.com:skrzepto/ansible-dotfiles.git ~/.ansible-dotfiles
ansible-playbook -K ~/.ansible-dotfiles/main.yml
```

### Dev tools

exa - show contents of folder
rg - ripgrep, search files recruse
bat - show contents of file with syntax highlighting
alacritty - gpu terminal
ranger - terminal file browser
fd - find but rusty
parallel - rusty version of xargs

*tools that need to be installed manually*

alacritty https://github.com/jwilm/alacritty
bat https://github.com/sharkdp/bat
parallel https://github.com/mmstick/parallel
safeyes https://slgobinath.github.io/SafeEyes/

#### Ranger terminal picture viewer
https://github.com/ranger/ranger/wiki/Image-Previews

# Credit where credit is due

Original repo was taken from Jeff Geerling and modified to my liking

```
## License

MIT / BSD

## Author Information

This role was created in 2015 by [Jeff Geerling](https://www.jeffgeerling.com/), author of [Ansible for DevOps](https://www.ansiblefordevops.com/).
```
