# Physical — product site

Public site for the **Physical** iOS/watchOS app, served via GitHub Pages as
plain static HTML (no Jekyll build; a `.nojekyll` file disables it).

## Pages
- `index.html` — marketing landing (`https://ryansan2001-source.github.io/physical/`)
- `support/index.html` — support + FAQ (App Store **Support URL**)
- `privacy/index.html` — privacy policy (App Store **Privacy Policy URL**)
- `assets/styles.css` — shared, theme-aware styles (brand coral/teal palette)
- `assets/screenshots/` — real screenshots go here; see the placeholder slots in `index.html`

## Keeping the privacy policy in sync
`privacy/index.html` mirrors the in-app policy, whose source of truth is
`PhysicalApp/Settings/PrivacyPolicy.md` in the app repo. **When the policy
changes, update both together** and bump the "Last updated" date in each.
