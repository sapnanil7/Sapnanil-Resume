# Sapnanil – LaTeX Resume


Auto-built with GitHub Actions and published on GitHub Pages.


- **View Online (Latest):** https://github.com/sapnanil7>/
- **Direct PDF:** https://<your-username>.github.io/<your-repo>/resume.pdf


## How it works
- Push changes to `main` → GitHub Actions compiles the LaTeX → deploys `site/` to Pages
- `site/index.html` embeds the freshly built `resume.pdf`


## Local build (optional)
Use `latexmk` if you want to test locally:
```bash
latexmk -pdf Sapnanil_Resume_LaTeX_Overleaf_Ready.tex