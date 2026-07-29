tsamb.github.io
===============

Personal website: a single static page, served at www.samuelrblackman.com.

- `index.html` — the whole site. One file, inline CSS, no JavaScript, no external
  dependencies, no build step.
- `.nojekyll` — publishes the repo verbatim; GitHub Pages skips Jekyll entirely.
- `rts/`, `sim/`, `sudoku/` — git submodules, kept so those paths keep resolving.
  Not linked from the root page. Clone with `git clone --recurse-submodules`.
