# 🖥️ VS Code Configuration Setup

This repository contains my personal **VS Code configuration**, including:

- User settings (`settings.json`)
- Keybindings (`keybindings.json`)
- Installed extensions (`extensions.txt`)

It is designed to help you quickly set up a consistent VS Code environment across machines.

---

## 📦 Installation Guide

### 1. Install VS Code

Install VS Code via Homebrew:

```bash
brew install --cask visual-studio-code
```

---

### 2. Apply Settings and Keybindings

Copy the repository files to your VS Code user directory:

```bash
cp settings.json ~/Library/Application\ Support/Code/User/settings.json
cp keybindings.json ~/Library/Application\ Support/Code/User/keybindings.json
```

> **Note:** On Windows, the user directory is usually:
> `%APPDATA%\Code\User\`

---

### 3. Install Extensions

This repository includes a list of extensions in `extensions.txt`. You can install them all with:

```bash
xargs -n 1 code --install-extension < extensions.txt
```

> Make sure the `code` command is available in your terminal.  
> (Open VS Code → `Cmd+Shift+P` → type `Shell Command: Install 'code' command`)

---

## 🧩 Folder Structure

```bash
.
├── README.md
├── extensions.txt
├── keybindings.json
└── settings.json
```

---

## 🧠 Notes

- Compatible with the terminal setup from my [terminal repository](../my-terminal-conf)

**Enjoy your configured VS Code! 🚀**
