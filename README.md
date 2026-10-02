# Interpretability for the Science of Training: Emergence, Prediction, and Steering (STEPS)

Website for the ICLR 2027 workshop. Hosted at https://science-of-training.github.io/.

## Structure
- `index.html` — main landing page (about, goals, CFP, schedule, speakers, organizers)
- `papers.html` — accepted papers (populated after notifications)
- `committee.html` — program committee
- `assets/styles.css` — site styles
- `materials/` — internal materials (gitignored, never published)

## Local preview
```sh
python3 -m http.server 8000 --directory .
# then open http://localhost:8000
```

## Deploy
Pushes to `main` are served automatically via GitHub Pages.
