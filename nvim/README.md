# Neovim Keybindings Reference

## Basic Operations
| Keybind | Description |
|---------|-------------|
| `jj` | Exit insert mode (alternative to `Esc`) |
| `WW` | Save file |
| `QQ` | Quit without saving |
| `<Space><Space>` | Clear search highlighting |
| `ss` | Clear search highlighting (alternative) |

## Navigation
| Keybind | Description |
|---------|-------------|
| `E` | Go to end of line |
| `B` | Go to beginning of line |
| `j` | Smart down (respects wrapped lines) |
| `k` | Smart up (respects wrapped lines) |

## Buffer Management
| Keybind | Description |
|---------|-------------|
| `tk` | Go to last buffer |
| `tj` | Go to first buffer |
| `th` | Previous buffer |
| `tl` | Next buffer |
| `td` | Delete buffer |

## Window Management
| Keybind | Description |
|---------|-------------|
| `Ctrl-w h` | Move to left window (file explorer) |
| `Ctrl-w l` | Move to right window (code editor) |
| `Ctrl-w j` | Move to window below |
| `Ctrl-w k` | Move to window above |
| `Ctrl-W,` | Decrease window width |
| `Ctrl-W.` | Increase window width |
| `<Space>qq` | Close split |

## File Explorer (NvimTree)
| Keybind | Description |
|---------|-------------|
| `<Space>e` | Toggle file explorer |

## LSP Features
| Keybind | Description |
|---------|-------------|
| `<Space>ee` | Insert Go error handling |

## Appearance
| Keybind | Description |
|---------|-------------|
| `TT` | Toggle transparency |
| `tw` | Toggle Twilight mode |

## Telescope (Fuzzy Finder)
| Keybind | Description |
|---------|-------------|
| `<Space>sf` | Search files |
| `<Space>sw` | Search current word |
| `<Space>sg` | Search by grep |
| `<Space>sd` | Search diagnostics |
| `<Space>sb` | Find existing buffers |
| `<Space>sS` | Git status |
| `<Space>sm` | Harpoon marks |

## Git Operations
| Keybind | Description |
|---------|-------------|
| `<Space>gs` | Open Neogit |
| `<Space>gc` | Commit |
| `<Space>gp` | Pull |
| `<Space>gP` | Push |
| `<Space>gb` | Git branches |
| `<Space>gB` | Git blame |

## LSP Navigation
| Keybind | Description |
|---------|-------------|
| `gd` | Go to definition |
| `gD` | Go to declaration |
| `K` | Show hover documentation |
| `<Space>rn` | Rename symbol |
| `<Space>ca` | Code actions |

## Trouble (Diagnostics)
| Keybind | Description |
|---------|-------------|
| `<Space>xx` | Toggle trouble |
| `<Space>xw` | Workspace diagnostics |
| `<Space>xd` | Document diagnostics |
| `<Space>xl` | Location list |
| `<Space>xq` | Quickfix list |

## Harpoon
| Keybind | Description |
|---------|-------------|
| `<Space>m` | Add file to harpoon |
| `<Space>ht` | Toggle harpoon menu |

## Debug
| Keybind | Description |
|---------|-------------|
| `<Space>dt` | Toggle DAP UI |
| `<Space>db` | Toggle breakpoint |
| `<Space>dc` | Continue |
| `<Space>dr` | Reset DAP UI |

## Notifications
| Keybind | Description |
|---------|-------------|
| `<Space>nn` | Dismiss notifications |

## Notes
- `<Space>` is the leader key
- Most keybindings work in normal mode unless specified otherwise 