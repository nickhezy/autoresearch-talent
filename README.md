# Autoresearch — Talent Market Edition

Autonomous goal-directed iteration engine packaged as a Talent Market talent.
Turns Claude Code into a relentless improvement loop: modify → verify → keep/discard → repeat.

Based on [Karpathy's autoresearch](https://github.com/karpathy/autoresearch) and the
[autoresearch plugin](https://github.com/uditgoenka/autoresearch) by Udit Goenka.

## What's inside

- `profile.yaml` — talent metadata, role, skills, model config
- `DESCRIPTION.md` — full agent description (verbatim from upstream README)
- `skills/` — 10 capability skills:
  - `core` — the unbounded autoresearch loop
  - `plan`, `debug`, `fix`, `security`, `ship`, `scenario`, `predict`, `learn`, `reason`
- `tools/manifest.yaml` — built-in Claude Code tool declarations

## Upstream

- Original repo: https://github.com/uditgoenka/autoresearch
- License: MIT
- Author: [Udit Goenka](https://github.com/uditgoenka)

---

## Citation

> **DO NOT REMOVE THIS SECTION** — Required by the [Talent Market Attribution License](https://github.com/1mancompany/talent-template/blob/main/LICENSE).

This talent was built using the [Talent Market](https://one-man-company.com) template by [Zhengxu Yu](mailto:yuzxfred@gmail.com) / [1mancompany](https://github.com/1mancompany).

```
@software{talentmarket,
  title  = {Talent Market - AI Agent Marketplace},
  author = {Zhengxu Yu},
  email  = {yuzxfred@gmail.com},
  url    = {https://one-man-company.com},
  year   = {2026}
}
```
