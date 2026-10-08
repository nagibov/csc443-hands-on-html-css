# CSC443 · Capstone: HTML + CSS portal

A hands-on session for **CSC443 Web Programming (LAU)**. In 30 small steps we build two pages that share one stylesheet:

- **Session A** (steps 01–15): `index.html`, the course home page (header, hero, syllabus cards, FAQ, contact form).
- **Session B** (steps 16–30): `dashboard.html`, a student dashboard (Grid layout, stat cards, progress, grades table, deadlines, dark mode).

Every step is one commit with a tag, so you can jump to any checkpoint.

## Setup

1. Install [VS Code](https://code.visualstudio.com/) and the **Live Server** extension (VS Code suggests it when you open this folder).
2. Clone the repo and open it in VS Code:
   ```bash
   git clone https://github.com/nagibov/csc443-capstone.git
   cd csc443-capstone
   code .
   ```
3. Right-click `index.html` → **Open with Live Server**.

## Catching up

Fell behind? Jump to the step the class is on (your own changes must be committed or stashed first):

```bash
git checkout step-07      # the project exactly as it is after step 7
git checkout main         # back to the finished project
```

To keep working from a checkpoint on your own branch: `git switch -c my-work step-07`.

Two shortcuts: `session-a` (home page finished) and `session-b` (everything finished).

## Steps

| Tag | Step | What we add | Files |
|---|---|---|---|
| `step-01` | A1 | Create the project and the HTML skeleton | `index.html` |
| `step-02` | A2 | Semantic page structure | `index.html` |
| `step-03` | A3 | An external stylesheet with a reset | `index.html`, `css/styles.css` |
| `step-04` | A4 | Design tokens with custom properties | `css/styles.css` |
| `step-05` | A5 | Header and navigation with Flexbox | `css/styles.css` |
| `step-06` | A6 | The hero section | `index.html` |
| `step-07` | A7 | Hero styling: gradient, fluid type, buttons | `css/styles.css` |
| `step-08` | A8 | Syllabus cards (HTML) | `index.html` |
| `step-09` | A9 | Cards with an auto-fit grid | `css/styles.css` |
| `step-10` | A10 | An FAQ with details / summary | `index.html` |
| `step-11` | A11 | FAQ styling | `css/styles.css` |
| `step-12` | A12 | The contact form (HTML) | `index.html` |
| `step-13` | A13 | Form styling and validation feedback | `css/styles.css` |
| `step-14` | A14 | Footer and a mobile-first media query | `css/styles.css` |
| `step-15` | A15 | Polish: sticky header, current page, motion | `index.html`, `css/styles.css` |
| `step-16` | B1 | A second page that shares everything | `dashboard.html` |
| `step-17` | B2 | Dashboard layout (HTML): sidebar + content | `dashboard.html` |
| `step-18` | B3 | Two-column layout with Grid areas | `css/styles.css` |
| `step-19` | B4 | Sidebar styling | `css/styles.css` |
| `step-20` | B5 | Stat cards (HTML) | `dashboard.html` |
| `step-21` | B6 | Stat cards: auto-fit grid and a scoped variable | `css/styles.css` |
| `step-22` | B7 | Course progress with native `<progress>` | `dashboard.html` |
| `step-23` | B8 | Panels, and labels aligned with subgrid | `css/styles.css` |
| `step-24` | B9 | The grades table (HTML) | `dashboard.html` |
| `step-25` | B10 | Table styling and status badges | `css/styles.css` |
| `step-26` | B11 | Upcoming deadlines | `dashboard.html`, `css/styles.css` |
| `step-27` | B12 | Arrange the widgets with named areas | `css/styles.css` |
| `step-28` | B13 | Refactor to mobile-first | `css/styles.css` |
| `step-29` | B14 | Dark mode by redefining the tokens | `css/styles.css` |
| `step-30` | B15 | Final polish: focus, motion, print | `css/styles.css` |
