# VSCode Settings

This repository contains my personal Visual Studio Code configuration files. These settings and keybindings are tailored to enhance productivity and streamline my workflow.

## Files

### `settings.json`
This file contains various VSCode settings, including:
- **Editor Enhancements**: Inline suggestions enabled, rulers set at 88 characters, and auto-save configured to save after a delay.
- **Git and Terminal**: Multi-line paste warnings disabled in the terminal, and `git.allowNoVerifyCommit` enabled.
- **Vim Mode**: Starts in insert mode for a smoother Vim experience.
- **Settings Sync**: Specific extensions ignored during sync.

### `keybindings.json`
This file defines custom keybindings for various commands, including:
- **Navigation**: Use `ctrl+h/j/k/l` for directional navigation.
- **Vim Mode Shortcuts**: Space-prefixed shortcuts for common actions like toggling the terminal (`space t`), finding files (`space f`), and more.
- **Editor Actions**: Bindings for moving lines (`shift+j/k`), renaming symbols (`space c r`), and revealing definitions (`space d`).
- **SCM Commands**: Shortcuts for staging/unstaging changes and navigating SCM resources.
- **Terminal and Quick Open Navigation**: Custom bindings for terminal and quick open navigation.

## How to Use
1. Copy the `settings.json` and `keybindings.json` files to your VSCode configuration directory (e.g., `~/.config/Code/User/`).
2. Restart VSCode to apply the changes.

Feel free to customize these settings further to suit your workflow!
