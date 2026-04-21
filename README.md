# HCI — 06.103.115

Two hand-coded websites built as coursework for **Human-Computer Interaction**, IIT Guwahati (Dr. Samit Bhattacharya, Prof. Pradeep Yammiyavar · NPTEL 106103115).

No frameworks. No build step. No dependencies. Just HTML, CSS, and vanilla JavaScript — so the principles demonstrated are *in* the code you can read.

---

## `lab/` — Field Lab

An interactive laboratory where every HCI principle is a working instrument instead of a paragraph of text. Dark scientific-journal aesthetic. Single scroll-driven page.

**Instruments included**

| § | Principle | What you can do |
|---|-----------|-----------------|
| 01 | **Fitts's Law** | Drag the width/distance sliders; click amber → mint targets; compare your MT against the prediction |
| 02 | **Hick's Law** | Choice-reaction timer across n = 2, 4, 8, 16; your RT plotted against log₂(n+1) |
| 03 | **Gestalt** | Toggle proximity, similarity, closure, continuity on the same set of dots |
| 04 | **Norman** | Bad-vs-good doors, stove mapping (linear vs spatial knobs), silent-vs-responsive feedback buttons |
| 05 | **Nielsen's 10** | Click any heuristic card — opens a modal with side-by-side UI mockups (violation vs respected) |
| 06 | **GOMS / KLM** | Build a task operator-by-operator and watch the seconds add up; three guided scenarios with step-by-step playback |
| 07 | **Color & Contrast** | Live WCAG contrast checker with AA/AAA pass-fail badges |
| 08 | **Accessibility Sim** | Screen-reader narration (real audio via Speech Synthesis), high-contrast, reduce-motion, colour-blind filter |

---

## `portfolio/` — Editorial Portfolio

An editorial magazine-style portfolio demonstrating the same principles applied to three fictional-but-realistic case studies. Cream-and-oxblood, large italic serif display type.

**Case studies**

- **Dharma** — Banking app redesign for first-time smartphone users (Fitts's Law + Hick's Law + Nielsen heuristics 5, 6, 8, 9)
- **Saanjh** — Rural-hospital registration kiosk (96 px hit targets, WCAG AAA, KLM before/after analysis)
- **Pravah** — NPTEL-style dashboard IA rebuild (card-sort-driven information architecture, cognitive walkthrough)

Plus a manifesto, a six-step UCD process diagram, a principles toolkit, and recognition quotes.

---

## Running locally

Any static file server will do:

```bash
# from this directory
python -m http.server 8000
# or
npx serve
```

Then open:

- [http://localhost:8000/lab/](http://localhost:8000/lab/)
- [http://localhost:8000/portfolio/](http://localhost:8000/portfolio/)

Or just double-click either `index.html` — they run straight from the file system.

---

## Principles applied across both sites

- **Norman (1988)** — affordance, mapping, feedback, constraints
- **Nielsen (1994)** — 10 usability heuristics
- **Shneiderman** — 8 golden rules of interface design
- **Fitts (1954)** · **Hick (1952)** — quantitative motor + cognitive laws
- **Gestalt** — proximity, similarity, closure, continuity, figure/ground
- **Card, Moran & Newell (1983)** — GOMS / KLM predictive modelling
- **Miller (1956)** — 7 ± 2 working-memory limit
- **WCAG 2.2 (2023)** — contrast, keyboard nav, reduced motion, screen-reader semantics
- **ISO 9241-210** — user-centred design lifecycle

---

## Credits

- Course: **HCI 06.103.115** · IIT Guwahati · [NPTEL 106103115](https://nptel.ac.in/courses/106103115)
- Instructors: Dr. Samit Bhattacharya · Prof. Pradeep Yammiyavar
- Built: 2026

---

*"The user is never wrong. If they cannot find the button, the button is hidden — even if it is in plain sight."*
