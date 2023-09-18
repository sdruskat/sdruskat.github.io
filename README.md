# Personal homepage of Stephan Druskat

Built with [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/).

The site is built in CI on pushes to `main`, and deployed to `gh-pages`.

# Build & serve locally

All content is in the `docs/` directory.

```bash
python3.11 -m venv .venv
. .venv/bin/activate
pip install --upgrade pip setuptools wheel
pip install -r requirements.txt
mkdocs serve
```
