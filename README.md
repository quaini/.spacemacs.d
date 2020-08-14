## Installation
1. Install [Emacs](https://www.gnu.org/software/emacs/download.html).
2. Install [Spacemacs](https://github.com/syl20bnr/spacemacs#install).
3. Delete your ```.spacemacs``` file and clone this repository.

```git clone https://github.com/quaini/.spacemacs.d.git ~/.spacemacs.d```

Note: A dotdirectory ```~/.spacemacs.d/``` can be used instead of a dotfile. If you want to use this option, move ```~/.spacemacs``` to ```~/.spacemacs.d/init.el```. [Source](https://github.com/syl20bnr/spacemacs/blob/develop/doc/DOCUMENTATION.org#dotfile-configuration)

## Cheatsheet

### General
Shortcut | Description 
---|---
`SPC f e d` | Open Configuration
`SPC f e R` | Reload Configuration

### Window Management `SPC w`
Shortcut | Description 
---|---
`SPC w /` | Vertical Split Window
`SPC w -` | Horizontal Split Window

## Bug Fixes
8/8/2020
- [MacOS-Catalina 10.15 issue with file system permissions](https://spin.atomicobject.com/2019/12/12/fixing-emacs-macos-catalina/)
