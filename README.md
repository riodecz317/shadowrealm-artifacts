# ShadowRealm Artifacts

A single, always-in-one-place index of Claude Artifacts created for this workspace, so they don't have to be re-found in old chat threads.

Open [`index.html`](index.html) in a browser to see the list. Each entry's title opens the full artifact HTML stored locally in [`artifacts/`](artifacts/) (works offline, no claude.ai session needed); the "live" link opens the current hosted version on claude.ai.

## Keeping it up to date

This index and the files under `artifacts/` are a static snapshot. To refresh after creating or updating artifacts, ask Claude (in this project folder) to **"update the artifact index"**. It will:

1. Pull the current artifact list from your Claude account
2. Re-fetch each artifact's full HTML content and overwrite its file in `artifacts/`
3. Regenerate `index.html`
4. Commit and push the change to this repo

## Repo

Private repo, pushed via GitHub CLI (`gh`). No GitHub Pages hosting is enabled (requires a paid plan for private repos) — view the dashboard by opening `index.html` locally, or by cloning/pulling this repo.
