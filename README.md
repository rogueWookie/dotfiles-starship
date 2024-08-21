# nvim dots

A collection of startship config files specific to me

- gruvbox.toml
- nord.toml

## To use ...

1. Check out repo to ~/.config/
2. Set up starship env path in shell rc config file
3. Source shell rc config file

```zsh
# ~/.zshrc
# Starship Config
export STARSHIP_CONFIG=~/.config/starship/nord.toml
eval "$(starship init zsh)"
```
