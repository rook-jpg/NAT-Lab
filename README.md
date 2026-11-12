# Portfolio + NAT project

Two separate things in one folder. Publish them as two different repos.

## 1. `nat-packet-tracer-lab/` - your project repo

Push this folder as its own repository. Its `README.md` renders as the repo page, and the screenshots inside `assets/` will show up.

```bash
cd nat-packet-tracer-lab
git init
git add .
git commit -m "NAT lab in Cisco Packet Tracer"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/nat-packet-tracer-lab.git
git push -u origin main
```

## 2. `index.html` - your portfolio site

This is a single self contained page. Publish it with GitHub Pages:

```bash
git init
git add .
git commit -m "Portfolio"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/portfolio.git
git push -u origin main
```

Then in the repo on GitHub: Settings, Pages, Source = "Deploy from a branch", branch `main`, folder `/ (root)`. Your site appears at `https://YOUR-USERNAME.github.io/portfolio/`.

Keep `assets/` next to `index.html` so the project screenshots load.

## Edit these before you publish

In `index.html`:

- Your programme, university and graduation year in the Education section.
- The two placeholder project cards. Replace them with real work or delete them.
- The GitHub, LinkedIn and email links in Contact. They point at generic pages right now.
- Your surname after "Hafsa" in the hero, if you want it there.
- The Skills lists, if any item does not match what you actually know.

In `nat-packet-tracer-lab/README.md`:

- The addressing plan table. It uses example values, so replace them with the addresses from your own lab.
- The topology table, if your device models or counts differ.
