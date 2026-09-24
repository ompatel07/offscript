# OFFSCRIPT® website

Responsive 11-page website and its source builder. The complete static site and downloadable ZIP are in [`outputs/`](outputs/).

## Preview locally

```powershell
python -m http.server 8000 --directory outputs
```

Then open http://localhost:8000/.

## Rebuild

Run `python work/build_site.py` from the repository root. It rebuilds the static pages and `outputs/OFFSCRIPT-complete-website.zip`.
