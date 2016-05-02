# fish ghq plugin

completions and keybinding for [ghq](https://github.com/motemen/ghq)

## Install

Only completions

```fish
curl -L https://raw.github.com/decors/fish-ghq/master/completions/ghq.fish \
  --create-dirs -o ~/.config/fish/completions/ghq.fish
```

With [fisherman](https://github.com/fisherman/fisherman)

```fish
fisher install decors/fish-ghq
```

## Keybinding

- Ctrl-g: repository finder using [fzf], [peco] or [percol].

## Variables

### `GHQ_FILTER`

If you want to change filter, run `set -U GHQ_FILTER peco (or percol)`.
Default filter is fzf if variable is not set.

## Completions

### Subcommands
![補完1](https://raw.githubusercontent.com/decors/various/master/images/ghq-screenshot1.png)

### Help
![補完2](https://raw.githubusercontent.com/decors/various/master/images/ghq-screenshot2.png)

### Repositories
![補完3](https://raw.githubusercontent.com/decors/various/master/images/ghq-screenshot3.png)

[peco]:https://github.com/peco/peco
[fzf]:https://github.com/junegunn/fzf
[percol]:https://github.com/mooz/percol
