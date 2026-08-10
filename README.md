# KAI Suite Web

Public **non-PHI** demo surfaces for the Khalpey AI Lab KAI Suite.

**Live:** https://zkhalpey.github.io/kai-suite/

| Page | Path |
|---|---|
| Hub | [index.html](index.html) |
| Researcher | [kai-researcher.html](kai-researcher.html) |
| Scribe | [kai-scribe.html](kai-scribe.html) |
| Patient | [kai-patient.html](kai-patient.html) |
| Doc | [kai-doc.html](kai-doc.html) |

## Non-PHI boundary
This repository contains **demonstration UI only**. No patient identifiers, operative logs, claims data, or unpublished IP claim language are included. Do not paste PHI into issues or PRs.

## Run locally / Codespaces
```bash
python3 -m http.server 8080
# open http://localhost:8080
```
Or open in GitHub Codespaces (devcontainer starts a static server on port 8080).

## Cite
See [CITATION.cff](CITATION.cff). After Zenodo is linked, prefer the release DOI over a floating commit URL.

```bibtex
@software{khalpey_kai_suite,
  author = {Khalpey, Zain},
  title  = {KAI Suite Web Demos},
  url    = {https://github.com/zkhalpey/kai-suite},
  version = {0.1.0},
  year   = {2026}
}
```

## License
MIT — see [LICENSE](LICENSE).

## Maintainers
Zain Khalpey, MD, PhD, FACS · zain@khalpey.ai · Khalpey AI Lab (ATARI AI)
