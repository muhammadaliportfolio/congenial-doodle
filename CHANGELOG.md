# CHANGELOG — Portfolio Upgrade

## Removed
- Single-page homepage layout stacking Skills/Client Roster inline
- Generic skill percentage bars
- Over-emphasized Certifications (moved to end, made compact)

## Added
- Services section (6 cards)
- Featured Case Studies page: Objective/Strategy/Execution/Tools/Result, verified numbers only
- Client Testimonials page with [ADD REAL CLIENT TESTIMONIAL] placeholders — no invented quotes
- Dark/Light mode toggle (persists via localStorage)
- SEO metadata: title + meta description per page, canonical URLs, Open Graph, Twitter card, Person + WebSite JSON-LD schema on homepage
- sitemap.xml and robots.txt
- Accessible focus states, one H1 per page

## Changed
- Homepage: Hero -> Stats -> About teaser -> Services -> Featured Case Studies teaser -> Full Portfolio Index -> Contact
- About page rewritten with "How I Work" 6-step framework
- Google Ads / Graphic Design / Video Editing pages show honest [ADD VERIFIED RESULT] placeholders instead of unsupported claims

## SEO Notes
- Canonical URLs and sitemap.xml target https://muhammadalibaran.com per the brief — only goes live once the domain is purchased and connected in GitHub Pages Settings + DNS

## GitHub Pages Deployment Notes
- All files use relative paths, no local paths — safe for GitHub Pages
- profile.png and both report PDFs live at repo root (no subfolder), since folder uploads were failing in the GitHub web UI
- To connect the custom domain later: buy muhammadalibaran.com, add a CNAME file with the domain to the repo root, set it in Settings -> Pages -> Custom domain, and point your registrar's DNS to GitHub Pages
