# FlowRead

A lightweight, single-file speed reader that runs entirely in your browser. No installs, no accounts, no server.

## What it does

FlowRead uses RSVP (Rapid Serial Visual Presentation) — it flashes words one at a time so your eyes don't have to scan. Great for getting through long articles or documents faster.

You can load content three ways:
- **PDF** — drag and drop or browse to upload
- **URL** — paste a link and it fetches the text
- **Plain text / Markdown** — paste directly or upload a `.txt` / `.md` file

## Features

- Adjustable reading speed (50–900 wpm)
- Progress bar with click-to-seek
- Library sidebar — keeps track of everything you've added with per-document reading progress
- Focus mode (`F`) — hides the UI so it's just you and the words
- Punctuation pause toggle — adds a slight delay after commas and periods
- Keyboard shortcuts: `Space` to play/pause, `←` / `→` to jump 10 words, `,` / `.` to slow down or speed up

## Usage

Just open `FlowRead.html` in any modern browser. That's it.

```
open FlowRead.html
```

Your library is saved to `localStorage`, so your docs and progress stick around between sessions.

## Tech

Vanilla JS, no build step, no dependencies except [PDF.js](https://mozilla.github.io/pdf.js/) (loaded from CDN) for PDF parsing. Everything else is plain HTML/CSS/JS in one file.
