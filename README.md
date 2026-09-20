# nicholasspell

Personal portfolio for Nicholas Spell, rebuilt as a static website (HTML, CSS, and a small amount of JavaScript).

This is a read-only rewrite of the earlier Flask portfolio. There is no login, no blog editor, and no backend.

## Pages

- `index.html` — about, featured projects, latest post, experience
- `projects.html` — project writeups
- `blog.html` — post list
- `posts/the-power-of-poetry.html` / `posts/capstone-project-report.html` — posts (PDFs in `assets/`)

## Run locally

From this directory:

```bash
python3 -m http.server 8080
```

Then open http://localhost:8080/

The files can also be opened directly in a browser, or dropped onto any static host.
