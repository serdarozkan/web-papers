# Serdar Ozkan Papers

This shared static site publishes web versions of Serdar Ozkan's papers.

## Structure

- `index.html`: papers landing page
- `assets/base.css`: shared site styling
- `papers.json`: registry used to rebuild the landing page and sitemap
- `site-config.json`: shared site defaults used by the publisher
- `<slug>/`: one folder per published paper

## File Lifecycle

- Original paper sources stay in the research folder, for example `~/Library/CloudStorage/Dropbox/.../PAPER/`.
- This `Web_Papers` directory is the published static site only.
- Any `<stem>-manuscript/` Quarto project used during conversion is a rebuildable intermediate, not a required long-term artifact.

That means a manuscript project can be regenerated from the source paper later if needed, while the already-published site here remains self-contained.

## Publishing

Run the tex-to-web publisher against a rendered manuscript project to refresh both the paper page and this shared site root.

Owner homepage: https://www.serdarozkan.me

Public base URL: https://papers.serdarozkan.me
