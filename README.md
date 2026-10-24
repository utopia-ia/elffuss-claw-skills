<div align="center">

<img src="assets/logo.svg" alt="" width="72">

# Elffuss Claw skills

**Teach Claw new jobs.**

Skills for [Elffuss Claw](https://claw.elffuss.com) that run entirely in the browser, with no Python and no backend, so you can
install and use them for real. Each one is a plain `SKILL.md` that the model follows.

[![License](https://img.shields.io/badge/license-Apache--2.0-1e6b52?style=flat-square)](LICENSE)
[![Runs in](https://img.shields.io/badge/runs%20in-your%20browser-1e6b52?style=flat-square)](https://claw.elffuss.com)

[Claw](https://claw.elffuss.com) · [Claw's repository](https://github.com/utopia-ia/elffuss-claw) · [Elffuss](https://elffuss.com)

</div>

> Elffuss Claw skills now lives in the UtopiaIA organization on GitHub, at github.com/utopia-ia/elffuss-claw-skills. It moved from github.com/KikoCis/elffuss-claw-skills on 23 October 2026; the old address redirects.

---

## The skills

| Skill | What it does |
|---|---|
| `jscad-3d-print` | A **printable 3D object (STL)** from a description: a 3D preview and an STL download (JSCAD). |
| `doc-to-excel` | The data of a document turned into a downloadable **Excel file with formulas and charts** (SheetJS and Chart.js). |
| `web-research` | Searches the internet and **closes a process** with something you can act on: a table, a checklist or a recommendation. |
| `arcade-game` | A playable **video game** (Flappy, Snake or Pong) in a single HTML file with a canvas. |
| `live-copilot` | A live skill for conversations: it takes the transcript as it comes, from Translator or typed, and builds a live document with signals, arguments and the next step. |

## How to use them

Install them from the **Skills** tab of Claw: this source is there by default. Each skill folder has its `SKILL.md` (the instructions
the model follows) and, where it applies, a tested `template.html`.

The skills run in your browser. `web-research` uses Claw's internet tool, which asks for your permission first; the rest never leave
your machine.

## Write your own

A skill is a folder with a `SKILL.md`: a short header that says when to use it, and the method. Look at any folder in `skills/`
and copy the shape.

## Licence

[Apache-2.0](LICENSE). See `NOTICE`.
