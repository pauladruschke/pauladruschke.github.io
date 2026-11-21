# Paula Druschke: personal academic website

Built with [Hugo](https://gohugo.io/) and the [PaperMod](https://github.com/adityatelange/hugo-PaperMod) theme, hosted on GitHub Pages at https://pauladruschke.github.io/.

## Preview locally

```bash
cd ~/Documents/GitHub/pauladruschke.github.io
hugo server
```

Then open http://localhost:1313. Stop the server with `Ctrl+C`.

## Where things live

- `content/_index.md`: home page (the About page)
- `content/research.md`: Research page
- `content/media.md`: Media page (writing, coverage, talks and videos)
- `content/contact.md`: Contact page
- `static/`: files served as they are (images, favicons)
- `assets/css/extended/custom.css`: all custom styling
- `config.yml`: site title, menu and settings

## Publishing

Commit and push to the `main` branch on GitHub (for example with GitHub Desktop). The workflow in `.github/workflows/hugo.yml` builds and deploys the site.
