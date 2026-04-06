<p align="center">
  <img src="https://raw.githubusercontent.com/Pirulug/vscode-pirulug-extension-pack/main/icon-pirulug.png" width="128" alt="Pirulug Logo">
</p>

<h1 align="center">Pirulug Extension Pack</h1>

<p align="center">
  <strong>The ultimate full-stack development toolkit for VS Code.</strong>
</p>

<p align="center">
  <a href="https://marketplace.visualstudio.com/items?itemName=pirulug.pirulug-extension-pack">
    <img src="https://img.shields.io/visual-studio-marketplace/v/pirulug.pirulug-extension-pack.svg?style=flat-square" alt="Version">
  </a>
  <a href="https://marketplace.visualstudio.com/items?itemName=pirulug.pirulug-extension-pack">
    <img src="https://img.shields.io/visual-studio-marketplace/i/pirulug.pirulug-extension-pack.svg?style=flat-square" alt="Installs">
  </a>
  <a href="https://marketplace.visualstudio.com/items?itemName=pirulug.pirulug-extension-pack&ssr=false#review">
    <img src="https://img.shields.io/visual-studio-marketplace/r/pirulug.pirulug-extension-pack.svg?style=flat-square" alt="Ratings">
  </a>
</p>

---

## Overview

The **Pirulug Extension Pack** is a curated collection of extensions designed to provide a cohesive, high-performance development environment. Whether you're building modern web interfaces with Bootstrap 5 or looking for a professional-grade aesthetic, this pack has everything you need.

## Included Extensions

This pack installs the following essential extensions:

### Aesthetics and UI
- **[Pirulug Theme](https://marketplace.visualstudio.com/items?itemName=pirulug.pirulug-theme)**: A meticulously crafted theme with dark and light variants optimized for long coding sessions.
- **[Pirulug Icons](https://marketplace.visualstudio.com/items?itemName=pirulug.pirulug-icons)**: A modern, minimalist icon theme that helps you identify file types at a glance.

### Productivity and Workflow
- **[Pirulug Keymap](https://marketplace.visualstudio.com/items?itemName=pirulug.pirulug-keymap)**: A set of powerful keyboard shortcuts designed to accelerate your workflow.

### Bootstrap 5 Development
- **[Bootstrap 5 Snippets](https://marketplace.visualstudio.com/items?itemName=pirulug.bootstrap5-snippets)**: A comprehensive collection of snippets for Bootstrap 5 components.
- **[Intellisense for Bootstrap 5](https://marketplace.visualstudio.com/items?itemName=pirulug.intellisense-bootstrap-5-by-pirulug)**: Advanced autocompletion, color previews, and hover documentation for Bootstrap 5 classes.

---

## Installation

1. Open **VS Code**.
2. Go to the **Extensions** view (`Ctrl+Shift+X`).
3. Search for `Pirulug Extension Pack`.
4. Click **Install**.
5. Restart VS Code (optional but recommended) to let the theme and icons take full effect.

## Development

If you want to contribute or build the theme from source:

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```
3. Generate the theme JSON files from the source files in `src/`:
   ```bash
   npm run build
   ```
4. Package the extension into a `.vsix` file:
   ```bash
   # Install vsce first if you haven't: npm install -g @vscode/vsce
   vsce package
   
## License

This extension pack is licensed under the [MIT License](LICENSE).

---

<p align="center">
  Made by <a href="https://github.com/Pirulug">Pirulug</a>
</p>
