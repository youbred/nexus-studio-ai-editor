# nexus-Web studio-ai-editor
AI-powered WYSIWYG website editor with Gemini, logo library, multi-page export – no server required
# Nexus Studio – AI Website Editor

**Nexus Studio** is a browser‑based WYSIWYG website builder with integrated **Gemini 1.5 Flash** AI.  
Create, edit, and export multi‑page websites with custom logos, background images, and responsive layouts – no server required.

## Features
- 🎨 Visual editor (click and edit)
- 🤖 Gemini AI assistant (improve text, change colors, apply modern styles)
- 🖼️ Logo library (IndexedDB – unlimited storage)
- 📄 Multi‑page projects
- 💾 Auto‑save (localStorage)
- 📱 Responsive preview (desktop, tablet, mobile)
- 🖨️ Export: PDF, ZIP (full site), standalone HTML template

## How to use
1. Download or clone this repository.
2. Open `index.html` in a modern browser (Chrome, Edge, Firefox).

## ✨ Features

- 🎨 **Visual editing** – click and edit text, buttons, images directly (contenteditable)
- 🤖 **Gemini AI assistant** – improve text, change colors, apply modern styles, or use custom prompts with image + file support
- 🖼️ **Logo & symbol library** – import PNG, JPG, SVG (sanitised), stored in IndexedDB (no size limit), insert with one click at cursor position
- 📄 **Multi‑page projects** – create, rename, delete pages (index.html, about.html, ...)
- 💾 **Auto‑save** – all project data is stored in localStorage + IndexedDB
- 📱 **Responsive preview** – switch between Desktop, Tablet, Mobile views
- 🖨️ **Export options**:
  - Current page as **PDF**
  - Full website as **ZIP** (standalone HTML files)
  - Current template as **single HTML file** (preserves background, inserted logos, all content)
- 🌙 **Dark / Light mode** – theme preference saved
- 🔁 **Undo / Redo** – Ctrl+Z / Ctrl+Y

## 🚀 Getting Started

### 1. Get a Gemini API Key

- Go to [Google AI Studio](https://aistudio.google.com/)
- Sign in with your Google account
- Click **Get API key** → create a key for **Gemini 1.5 Flash**
- Copy the key (starts with `AIza...`)

### 2. Launch Nexus Studio

Simply double‑click `index.html` – it works offline (no web server required).

### 3. Paste your API key

In the left sidebar, enter your Gemini API key. The AI features will activate immediately.

## 🧰 How to Use

| Action | How to do it |
|--------|---------------|
| Edit text | Click directly on the page and type |
| Change layout | Select “Centered”, “Sidebar”, or “Bottom” in the sidebar |
| Add background image | Click “Background Image” (top bar) and choose an image |
| Import a logo | Click “Import Logo/Symbol” (top bar) – appears in the library |
| Insert logo into page | Click any thumbnail in the “Logo Library” section |
| Delete a single logo | Hover over a thumbnail and click the red ✕ |
| Ask the AI | Type a request in the chat (e.g., “make the button green and add a shadow”) or use shortcut buttons |
| Create a new page | Click “Add page” and enter a name like `services.html` |
| Export current page as PDF | Click “PDF” button |
| Export full website as ZIP | Click “ZIP Site” – downloads all pages as standalone HTML files |
| Export current template | Click “Export Template” – saves a complete HTML file with all inserted logos and background |

## ⌨️ Keyboard Shortcuts

- `Ctrl + S` – manually save project
- `Ctrl + Z` – undo last content change
- `Ctrl + Y` – redo
- `Ctrl + P` – export current page as PDF

## 🛠️ Technologies Used

- HTML5 / CSS3 (Flexbox, Grid, custom properties)
- Vanilla JavaScript (ES2020)
- [Google Gemini 1.5 Flash API](https://ai.google.dev/gemini-api)
- [IndexedDB](https://developer.mozilla.org/en-US/docs/Web/API/IndexedDB_API) – for logo storage
- [html2canvas](https://html2canvas.hertzen.com/) – screenshot for AI
- [html2pdf.js](https://github.com/eKoopmans/html2pdf.js) – PDF export
- [JSZip](https://stuk.github.io/jszip/) – ZIP export
- [DOMPurify](https://github.com/cure53/DOMPurify) – SVG sanitisation

## 📁 Repository Structure
nexus-studio/
├── index.html # Full application (single file)
├── README.md # Documentation
├── RECRUITMENT.md # Join the team
└── screenshot.png # (optional) preview image
