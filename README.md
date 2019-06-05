# insight-github-guide
Guide to using GitHub for Insight Fellows.

Slides providing overview of contributing with teams to GitHub repos.

Online slides can be found [here](https://zhampel.github.io/insight-github-guide/#/).

## Usage

The slides for this talk can be generated via:

```bash
virtualenv -p /usr/local/bin/python3 venv
source venv/bin/activate
pip install -r requirements.txt

jupyter nbconvert notebooks/insight_github_guide_slides.ipynb --to slides --post serve --template output_toggle.tpl --SlidesExporter.reveal_transition=none --SlidesExporter.reveal_scroll=True --SlidesExporter.reveal_theme=serif
```

# Informative Section Title
Detailed details (but not too detailed) regarding this section,
especially with respect to general usage, requirements, limitations
of your software project.
