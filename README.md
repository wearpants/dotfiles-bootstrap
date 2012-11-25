# dotfiles-bootstrap
Scripts to create dotfiles, my-style.

## Overview
Config files live directly in their usual place, in `~/.some_file`. 
git's repo lives in `$DOTFILES_DIR` (`~/.dotfiles` by default). To 
interact with the repo (commit, etc.), you must be in this directory 
(*not* in `~`) and reference files with a relative path 
(`../.some_file`).

Ignores live in `~/.dotfiles_ignore` (see `man gitignore` for more). By 
default, everything is excluded.

## Commands
To specify an alternate location for the git repo, call like 
`DOTFILES_DIR=/path/to/repo init`.

**init** create a new empty dotfiles setup
**clone http://...** clone and checkout an existing dotfiles repo
