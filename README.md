# Settlers Documentation

Documentation site for the Settlers geolocation strategy game. Built with [Zensical](https://zensical.dev).

## Prerequisites

- Python 3.13+ (see `.tool-versions`)
- [asdf](https://asdf-vm.com/) (optional, for version management)

## Quick Start

```bash
# Activate virtual environment
source .venv/bin/activate

# Run dev server with hot-reload
zensical serve -o
```

Opens at `http://localhost:8000` with auto-reload on file changes.

## Commands

| Command | Description |
|---------|-------------|
| `zensical serve` | Start dev server (port 8000) |
| `zensical serve -a 0.0.0.0:8080` | Custom host/port |
| `zensical serve -o` | Auto-open in browser |
| `zensical build` | Build static site to `site/` |

## Project Structure

```
docs/
├── index.md              # Home page
├── guides/               # Game guides (getting-started, mechanics, etc.)
│   ├── getting-started.md
│   ├── game-mechanics.md
│   ├── clan-system.md
│   ├── territory-system.md
│   ├── referral-system.md
│   └── roadmap.md
├── assets/               # Images
└── ru/                   # Russian translations
```

## Deploy

Built output goes to `site/` directory. Deploy to any static hosting (Vercel, Netlify, GitHub Pages).
