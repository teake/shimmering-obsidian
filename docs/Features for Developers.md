---
nav_order: 2
---

# Features for Developers

<!-- MarkdownTOC -->

- [Plugin Search](#plugin-search)
- [Cheatsheets](#cheatsheets)
- [Open various folders related to development](#open-various-folders-related-to-development)
- [Local plugins](#local-plugins)
- [Vault-related features](#vault-related-features)
- [Beta Plugins](#beta-plugins)
- [Obsidian Version Information](#obsidian-version-information)
- [Browse Obsidian via Terminal](#browse-obsidian-via-terminal)

<!-- /MarkdownTOC -->

## Plugin Search
➡️ Refer to the [Plugin & Theme Search](Plugin%20and%20Theme%20Search.md#Plugins) for the Information on the theme search capabilities. Particularly useful for plugin developers should be:
- the `fn + ↵` command to clone a plugin.
- the [GitHub issue search](Plugin%20and%20Theme%20Search.md#%F0%9F%86%95-Searching-GitHub-Issues)
- `⌃ + ↵` to see and copy plugin IDs

<img src="https://user-images.githubusercontent.com/73286100/139559362-747b0c57-c29b-45b5-bc62-4ab53c0718c5.gif" alt="Issue Search" width=60%>

## Cheatsheets
**`o`: Quickly Access Various `C`heatsheets for developing plugins and designing themes in Obsidian.**
- The cheatsheets will be opened via the macOS Quick Look feature, so you can simply close them by pressing `space`.

<img src="https://i.imgur.com/nVT687p.png" alt="Cheatsheets" width=20%>

## Open various folders related to development
- Refer to the section on [Quick Access to hidden folders](Utility%20Features.md#Open-Various-Folders) for further information.
- To quickly open local plugin folders in `.obsidian/plugins/`, use to the [Settings & Local Plugin Search](Settings%20and%20Local%20Plugin%20Search.md).

## Local plugins
Refer to the section on [Settings & Local Plugin Search](Settings%20and%20Local%20Plugin%20Search.md) for further information on how to:
- Open local Folders in Finder or the Terminal.
- Run `git pull` in a local repository.

## Vault-related features
➡️ Refer to the documentation of the [Vault Switcher](Vault%20Switcher.md) for information on how to switch vaults quickly and open the the vault root in Finder or the Terminal.

## Beta Plugins
**`obeta`: Access `beta`-plugin-related commands.**
- Add a new plugin to your beta plugins.
- Open the repository of a beta plugin.
	- Press `⌥ + ↵` to copy the GitHub repository URL to your clipboard. When Discord is the frontmost app, the copied link will be surrounded with `<` `>` for more convenient pasting in the Discord Desktop app (disables auto-preview).
- Update all beta plugins.
- All commands require the [BRAT Plugin](https://github.com/TfTHacker/obsidian42-brat).
- Install a new theme.

## Obsidian Version Information
**Snippet Trigger: `!oversion`**
Type `!oversion` in any text field, and Alfred will output your current Mac and Obsidian version. Useful for people frequently creating bug reports.

## Browse Obsidian via Terminal
Do want to navigate your vault from within the Terminal? [Have a look.](https://gist.github.com/chrisgrieser/4e4d21d701f70b0eef5e25496583e38e)

![Vault Navigation in the Terminal](images/terminal-vault-navigation.png)

(Thanks to `@jack of some trades`.)
