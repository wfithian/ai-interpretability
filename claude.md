# AI Interpretability Reading Group Website

Quarto website for the UC Berkeley graduate reading group "AI Interpretability: Meaning, Methods, and Limits" (Spring 2026).

## Quick Commands

```bash
# Preview locally (runs in background, auto-refreshes)
quarto preview

# Render site
quarto render

# Publish to GitHub Pages
quarto publish gh-pages --no-prompt
```

## Project Structure

- `index.qmd` - Landing page with logistics, description, and reading schedule tables
- `syllabus.qmd` - Full syllabus with paper summaries and descriptions
- `_quarto.yml` - Quarto project configuration
- `styles.css` - Custom CSS (UC Berkeley colors)

## Schedule Structure

The course has 15 weeks (Spring 2026: Jan 23 - May 8, spring recess Mar 23-27):

- **Part I: Meaning (Weeks 1-4)** - Framing interpretability, neuroscience connections, circuits, safety strategy
- **Part II: Methods (Weeks 5-13)** - ROME, steering vectors, behavioral directions, unlearning, latent knowledge, causal scrubbing, causal abstractions, SAEs, large-scale mech interp
- **Part III: Limits (Weeks 14-15)** - Mesa-optimization, deceptive interpretability

## Deployment

- **Main branch**: Source files (`.qmd`)
- **gh-pages branch**: Built site (managed by `quarto publish`)
- **Live site**: https://wfithian.github.io/ai-interpretability/

No need to commit to deploy - `quarto publish gh-pages` handles building and pushing to the gh-pages branch directly.

## Conventions

- Dates are single days (Fridays) for weekly meetings, e.g., "Jan 23" not "Jan 20-23"
- Meeting time: Fridays 1-2:30pm in Latimer 120
- Paper summaries in syllabus.qmd are one sentence in italics
- Reading schedule tables in index.qmd use format: Week | Date | Topic | Reading
