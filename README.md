# ⚡ Prompt Clipboard

A lightweight, Windows-style desktop app for managing your LLM prompts — built as a single HTML file. No installation, no backend, no dependencies.

![App Preview](https://img.shields.io/badge/Type-Single%20HTML%20File-7c6af7?style=flat-square) ![License](https://img.shields.io/badge/License-MIT-green?style=flat-square) ![Works Offline](https://img.shields.io/badge/Works-Offline-2ecc71?style=flat-square)

---

## ✨ Features

- **⎘ One-click copy** — hover any prompt card and copy instantly to clipboard
- **✎ Inline editing** — edit title, body, and category directly in the card (`Ctrl+Enter` to save)
- **♥ Favorites** — pin your most-used prompts to the top
- **🗂 Sidebar navigation** — filter by All, Favorites, or category
- **🔍 Live search** — finds prompts by title, content, or tag instantly
- **`[VARIABLE]` detection** — placeholder chips remind you what to fill in before using
- **💾 Persistent storage** — all prompts auto-save to browser localStorage
- **🌙 Dark theme** — easy on the eyes for long sessions

---

## 🚀 Getting Started

### Option 1 — Use directly in browser (no setup)

1. Download `PromptClipboard.html`
2. Double-click to open in your browser
3. Start adding prompts!

### Option 2 — Run as a desktop app (Chrome/Edge)

1. Open `PromptClipboard.html` in Chrome or Edge
2. Go to **Menu (⋮) → More tools → Create shortcut**
3. Check **"Open as window"**
4. Click **Create** — now it lives in your taskbar like a native app 🎉

### Option 3 — Host on GitHub Pages (access from anywhere)

1. Fork or clone this repo
2. Go to **Settings → Pages**
3. Set source to **main branch → / (root)**
4. Your app will be live at `https://yourusername.github.io/prompt-clipboard`

---

## 📁 Project Structure

```
prompt-clipboard/
└── PromptClipboard.html   # The entire app — one file
└── README.md
```

Everything is self-contained in a single HTML file. No npm, no build step, no server needed.

---

## 🗂 Prompt Categories

| Category | Use case |
|----------|----------|
| **General** | Everyday tasks, explanations, brainstorming |
| **Writing** | Editing, rewriting, content creation |
| **Analysis** | Summarizing, extracting insights |
| **Coding** | Debugging, code review, documentation |
| **Roleplay** | Expert personas, simulations |
| **Research** | Outlines, literature, fact-finding |

---

## 💡 Tips

- Use `[VARIABLE_NAME]` in your prompts as placeholders — they show up as visual chips so you never forget to fill them in
- Press `Ctrl+Enter` while editing to save quickly
- Star your most-used prompts — they always stay at the top
- All data is stored in your browser's localStorage, so it persists across sessions on the same device

---

## 🛠 Built With

Pure HTML, CSS, and vanilla JavaScript. No frameworks, no libraries, no internet connection required after download.

---

## 📄 License

MIT — free to use, modify, and share.
