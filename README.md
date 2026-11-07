# dotfiles
Arch Linux + Hyprland dotfiles, managed with chezmoi

## Bootstrap

```sh
archinstall --config https://raw.githubusercontent.com/yi1306c12-lab/dotfiles/main/archinstall/user_configuration.json
reboot 0
```

```sh
chezmoi init --apply yi1306c12-lab
```

```sh
gh auth login
```
