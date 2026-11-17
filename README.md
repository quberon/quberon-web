# Quberon website

Static website for Quberon.

## Local preview

Open `index.html` in a browser, or run:

```bash
python3 -m http.server 8000
```

Then visit <http://localhost:8000>.

## Publishing

The site is plain HTML/CSS with no build step. The GitHub Pages workflow in
`.github/workflows/pages.yml` publishes the repository root when changes land
on `main`.

## Repository policy

This is the public website for now. Pull-request review is intentionally not
required on this repository; changes are still made by commit and can be
inspected in git history.
