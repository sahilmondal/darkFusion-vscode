<p align="center">
  <img alt="Dark Fusion Logo" src="https://raw.githubusercontent.com/sahilmondal/darkFusion-vscode/main/images/Logo.png" width="100" />
</p>
<h1 align="center">
  Dark Fusion Theme for VS Code
</h1>
<p align="center">
  A minimal, dark theme for <a href="https://dark-fusion.vercel.app/">VS Code</a>.
</p>
<!-- <p align="center">
  <a href="https://marketplace.visualstudio.com/items?itemName=brittanychiang.halcyon-vscode">
    <img alt="Version" src="https://img.shields.io/visual-studio-marketplace/v/brittanychiang.halcyon-vscode?color=brightgreen" />
  </a>
  <a href="https://marketplace.visualstudio.com/items?itemName=brittanychiang.halcyon-vscode">
    <img alt="Downloads" src="https://img.shields.io/visual-studio-marketplace/d/brittanychiang.halcyon-vscode" />
  </a>
  <a href="https://marketplace.visualstudio.com/items?itemName=brittanychiang.halcyon-vscode">
    <img alt="Installs" src="https://img.shields.io/visual-studio-marketplace/i/brittanychiang.halcyon-vscode" />
  </a>
</p> -->

![demo](https://raw.githubusercontent.com/sahilmondal/darkFusion-vscode/main/images/demo.png)

## Installation via VS Code

1. Open **Extensions** sidebar panel in VS Code. `View → Extensions`
2. Search for `Dark Fusion`
3. Click **Install** to install it
4. Click **Reload** to reload the editor
5. Code > Preferences > Color Theme > **Dark Fusion**

## Manual Installation

Read the [VSC Extension Quickstart Guide](https://raw.githubusercontent.com/sahilmondal/darkFusion-vscode/main/vsc-extension-quickstart.md)

## Icon Theme

The file icon theme seen in the screenshot above is [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme) with these settings:

```json
  "material-icon-theme.folders.color": "#8695b7",
  "material-icon-theme.folders.theme": "specific",
  "material-icon-theme.hidesExplorerArrows": true,
```

## Color Reference

### Syntax Colors

|                                 Color                                  | Usage                                           |
| :--------------------------------------------------------------------: | ----------------------------------------------- |
| ![#c3a6ff](https://via.placeholder.com/10/c3a6ff.png?text=+) `#c3a6ff` | Keywords, constants, template literals          |
| ![#ffd580](https://via.placeholder.com/10/ffd580.png?text=+) `#ffd580` | Functions, classes, object literal keys         |
| ![#ffae57](https://via.placeholder.com/10/ffae57.png?text=+) `#ffae57` | Constants, operators                            |
| ![#bae67e](https://via.placeholder.com/10/bae67e.png?text=+) `#bae67e` | Strings, markdown headings                      |
| ![#5ccfe6](https://via.placeholder.com/10/5ccfe6.png?text=+) `#5ccfe6` | Special keywords, classes, markdown code blocks |
| ![#a2aabc](https://via.placeholder.com/10/a2aabc.png?text=+) `#a2aabc` | Variables, property names, tags                 |

### UI Colors

|                                 Color                                  | Usage                                      |
| :--------------------------------------------------------------------: | ------------------------------------------ |
| ![#0e0921](https://via.placeholder.com/10/0e0921.png?text=+) `#0e0921` | Workbench background                       |
| ![#100f2e](https://via.placeholder.com/10/100f2e.png?text=+) `#100f2e` | Editor background                          |
| ![#8695b7](https://via.placeholder.com/10/8695b7.png?text=+) `#8695b7` | Status bar text, buttons, etc              |
| ![#d7dce2](https://via.placeholder.com/10/d7dce2.png?text=+) `#d7dce2` | Active text, anything that should be white |
| ![#8652ff](https://via.placeholder.com/10/8652ff.png?text=+) `#8652ff` | Main-Borders                               |
| ![#4d3fa4](https://via.placeholder.com/10/4d3fa4.png?text=+) `#4d3fa4` | Highlights / secondary Bg                  |
| ![#a9d03f](https://via.placeholder.com/10/a9d03f.png?text=+) `#a9d03f` | Accent, list tree titles, badges, etc      |
| ![#5852ff](https://via.placeholder.com/10/5852ff.png?text=+) `#5852ff` | Addition highlights                        |
| ![#ef6b73](https://via.placeholder.com/10/ef6b73.png?text=+) `#ef6b73` | Deletion highlights, errors, warnings      |
|                                                                        |

## Theming Reference

[VS Code Theme Color Reference](https://code.visualstudio.com/docs/getstarted/theme-color-reference)

[VS Code Theme Documentation](https://code.visualstudio.com/docs/extensions/themes-snippets-colorizers)

[VS Code Publishing Extensions](https://code.visualstudio.com/docs/extensions/publish-extension)

Syntax colors are based on [Halcyon](https://github.com/bchiang7/halcyon-vscode)

```bash
vsce publish patch/minor/major
```

<!-- ## Shameless Plug -->

<!-- Dark Fusion is also available for [Sublime Text, Atom, iTerm, and more!](https://halcyon-theme.netlify.com/). -->
