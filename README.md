### How It Works
#### Symlinked Files

The installation creates symlinks from your home directory to the dotfiles repository. This allows you to version control your configuration while keeping files in their expected locations.

### Quick Start
```bash
git clone git@github.com:wung-s/dotfile.git ~/.dotfile
cd ~/.dotfile
```

### Creating Symlink
```
#example
$ ln -sf "$PROJECT_DIR/claude/CLAUDE.md" ~/.claude/CLAUDE.md
```