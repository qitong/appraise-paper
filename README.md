# appraise-paper

A Claude Code skill for critically analysing a primary research paper. It is based on the three-phase, seven-step framework in:

> Cornwell J. *How to read a research paper.* Nature 654, 828–829 (2026).

- **Phase 1 — Aerial view**: (1) broad overview from the abstract and figures, (2) core research question, (3) knowledge gap
- **Phase 2 — Interrogation**: (4) methodology (tools, power, controls, data and code availability), (5) form your own conclusion from the results and figures *before* reading the discussion
- **Phase 3 — Verdict**: (6) reconcile the authors' conclusions with yours, (7) alternative explanations, confounders, limitations, conflicts of interest

There are two modes. **Coaching** walks you through the steps so you build your own appraisal skills. **Review** has Claude produce a structured appraisal report. The skill text is in Chinese.

Related skills: [develop-question](https://github.com/qitong/develop-question), [develop-oncology-question](https://github.com/qitong/develop-oncology-question).

## Install

```bash
git clone https://github.com/qitong/appraise-paper ~/.claude/skills/appraise-paper
```

Then upload a paper and ask "批判性精读这篇", or run `/appraise-paper`.
