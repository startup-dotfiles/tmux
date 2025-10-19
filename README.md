# Dotfiles --- tmux terminal multiplexer

```sh
# Backup/Rename
[ -d $HOME/.config/tmux ] mv $HOME/.config/tmux $HOME/.config/tmux.bak
# Clone
git clone https://github.com/startup-dotfiles/tmux $HOME/.config/tmux

# These files can be deleted after installation.
rm -r README.md LICENSE .git/ .gitignore
```

## Installed Plugins

- Plugin Manager:
  - [tpm](https://github.com/tmux-plugins/tpm)
- Theme:
  - [catppuccin](https://github.com/catppuccin/tmux)
- Status Lines:
  - [tmux-pomodoro-plus](https://github.com/olimorris/tmux-pomodoro-plus)
  - [tmux-cpu](https://github.com/tmux-plugins/tmux-cpu)
- Enhancement:
  - [tmux-yank](https://github.com/tmux-plugins/tmux-yank) (depndencies: wl-clipboard)
  - [tmux-menus](https://github.com/jaclu/tmux-menus)
- Search & Jump
  - [tmux-fzf-url](https://github.com/wfxr/tmux-fzf-url) (dependencies: fzf)
  - [tmux-fzf-links](https://github.com/alberti42/tmux-fzf-links) (dependencies: fzf)

## Keybindings

- Prefix key: <kbd>M-a</kbd> (default: C-b)

| Action                    | Key                                        |
| :------------------------ | :----------------------------------------- |
| Install plugins           |  `prefix` + <kbd>I</kbd>                   |
| Update plugins            |  `prefix` + <kbd>U</kbd>                   |
| Remove/uninstall plugins  |  `prefix` + <kbd>alt</kbd> + <kbd>u</kbd>  |
| Reload tmux               |  `prefix` + <kbd>r</kbd>                   |
