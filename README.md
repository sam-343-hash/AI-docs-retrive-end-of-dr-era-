# MedRetrieve

A single-page demo of an AI-style clinical document retrieval interface. Type a clinical question and it ranks results from a small sample corpus of guidelines, drug monographs, and research abstracts — highlighting matched terms and showing a relevance score for each source.

**[View the live demo](#)** *(add your GitHub Pages link here once enabled)*

## What it does

- Weighted keyword/term-overlap search across a 12-document sample corpus (guidelines, drug monographs, research abstracts)
- Filters by source type
- Shows the actual source passage with matches highlighted, rather than generating a summarized answer
- Includes a short explainer on how the demo's scoring maps onto a real retrieval-augmented generation (RAG) pipeline (embeddings + vector search)

## Running it

This is a single self-contained HTML file with no build step and no dependencies.

- **Locally:** open `index.html` in any browser.
- **Hosted:** enable GitHub Pages on this repo (Settings → Pages → Deploy from branch → `main` → `/root`) and it will be served directly.

## Status

This is a prototype/demo interface only. It runs entirely in the browser on a small fixed sample corpus using simple keyword matching — it is **not** connected to a real medical database, has not been clinically validated, and must not be used to inform patient care.

## License

MIT — see [LICENSE](LICENSE).
