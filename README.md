# Linux Command Cheatsheet

A searchable, single-page Linux command reference. Everything lives in one static `index.html` file with no build step.

## Features

- Commands grouped into sections: Files & Directories, Viewing & Editing, Users & Permissions, Process & Task Management, Networking, Disk & Filesystem, Text Search, System Admin, Security & Firewall, and Archiving (zip/tar)
- Each command has a short description, with extra flags and tips inline
- Live search box that filters commands as you type and hides sections with no matches

## Tech stack

- Plain HTML, CSS and vanilla JavaScript
- Google Fonts (JetBrains Mono, Syne)
- Vercel Web Analytics script (`/_vercel/insights/script.js`), which only loads when deployed on Vercel with Analytics enabled

## Project structure

```
.
└── index.html   # markup, styles and search script
```

## Running locally

Open `index.html` directly in a browser. No installation is required.

## Deployment

The page is deployed as a static site on Vercel; any static host will also work (the analytics script will simply 404 outside Vercel).
