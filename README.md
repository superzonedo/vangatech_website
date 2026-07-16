# VangaTech 前域科技 — Company Site

Single-page company site for the Claude Partner Network application. Bilingual (English default, toggle to 中文), built as one static HTML file — no build step needed.

## Files

- `index.html` — the whole site (HTML + CSS + JS in one file)

## Editing

Open `index.html` in any editor. Text that appears in both languages is marked with `data-en="..."` and `data-zh="..."` attributes on the same element — update both when you change copy, or the language toggle will show stale text on one side.

Case files (the 4 project cards) live in the `<section id="cases">` block. Each one is a `.case` div with a `data-en` / `data-zh` pair on every text element — copy an existing block to add a new case.

## Viewing locally

No install needed. Just open `index.html` directly in a browser, or from a terminal:

```
open index.html        # macOS
start index.html        # Windows
```

## Deploying with GitHub Pages

Once this is pushed to GitHub (see setup steps below), turn on Pages in the repo's **Settings → Pages** tab, set the source to the `main` branch and `/ (root)` folder, and save. GitHub will give you a URL like `https://<your-username>.github.io/<repo-name>/` within a minute or two — that's the link to put in the CPN application.

## Contact

info@vangatechai.com
