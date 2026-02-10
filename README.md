# znk-personal-website

Personal site for Jesús Antonio Sánchez Méndez, hosted on GitHub Pages.

## Structure
- `index.html` — landing page with hero, highlights, CTA
- `about.html` — background, focus areas, community highlights
- `projects.html` — LinkedIn-sourced project snapshots
- `styles.css` — shared styling

## Deployment
- Main branch contains the editable source
- `gh-pages` branch mirrors main for static hosting
- Hosted via GitHub Pages at https://znk-agent.github.io/znk-personal-website/

To update the live site:
```bash
# edit files on main
npm run lint # (if you add tooling later)
git commit -m "feat: update content"
git push origin main
# sync gh-pages if needed
git checkout gh-pages && git merge main && git push origin gh-pages
```
