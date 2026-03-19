# Middleton Island Marine Biological Station — Website

Static HTML website for the [Institute for Seabird Research and Conservation](https://middletonisland.org), supporting the Middleton Island Marine Biological Station in the Gulf of Alaska.

## Pages

| File | Description |
|------|-------------|
| `index.html` | Homepage with video hero, stats, team, and timeline |
| `about.html` | Island history, location, and FAQ |
| `research.html` | Research areas, news, and scientific timeline |
| `team.html` | Researcher profiles and affiliations |
| `gallery.html` | Photo gallery (People, Island, Research) with lightbox |
| `contact.html` | Contact information and collaboration inquiries |
| `donations.html` | Donations page with Infinite Giving widget |
| `endowment.html` | Endowment case statement and legacy giving information |
| `research-products.html` | Full bibliography (117 publications, 1979–2025) |

## Design

- Ocean-themed color palette with CSS custom properties
- Google Fonts: Cormorant Garamond (serif) and Outfit (sans-serif)
- Responsive layout for desktop, tablet, and mobile
- Self-contained — all CSS and JavaScript embedded per page, no build step required

## Media

Local images are stored in `media/`. The homepage video is hosted on the WordPress media library at middletonisland.org.

## Deployment

These are static HTML files with no server-side requirements. Upload the directory to any static host (GitHub Pages, Netlify, Cloudflare Pages, etc.) or paste page content into WordPress Custom HTML blocks.

## Notes

- Donation processing via [Infinite Giving](https://infinitegiving.com) (App ID: CO5PQRRJS)
- All pages share a consistent header/footer and navigation structure
- The `archive/` folder contains earlier drafts and is not part of the live site
