# LaTeX Resume - Shantanu Maratha

Professional resume built with LaTeX.

## Automatic PDF Generation

This repository uses GitHub Actions to automatically compile `resume.tex` into `resume.pdf` on every push to the main branch.

The PDF is available via GitHub Pages at: `https://[your-username].github.io/[repo-name]/resume.pdf`

## Manual Build

```bash
pdflatex resume.tex
```

## Setup GitHub Pages

1. Go to repository Settings → Pages
2. Source: Deploy from branch
3. Branch: main
4. Folder: / (root)
5. Save

Your resume will be automatically available at the GitHub Pages URL after each push.
