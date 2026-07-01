# Canaan AI — Releases

Public update channel for **Canaan AI** (the app source is private).

- `updates.json` — the manifest the app polls on launch to detect new versions.
- Each version's installer is attached to the matching GitHub **Release** (tag `vX.Y.Z`).

The app fetches `https://raw.githubusercontent.com/thublihl/canaan-ai-releases/main/updates.json`,
compares versions, and offers a one-click in-app update.
