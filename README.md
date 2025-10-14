# Rachel Parkinson Lab Website

This is the source code for Rachel Parkinson's Lab webpage, built with Jekyll and the [Noir theme](https://github.com/essentialenemy/noir).

## Local Development

To run the site locally for testing:

1. Make sure you have Ruby and Bundler installed
2. Install dependencies:
   ```bash
   bundle install
   ```
3. Run the local server:
   ```bash
   bundle exec jekyll serve
   ```
4. View the site at `http://127.0.0.1:4000`

## Adding Content

### Blog Posts

Create new posts in the `_posts` directory with the format: `YYYY-MM-DD-title.md`

Example front matter:
```yaml
---
layout: post
title: Your Post Title
categories: [Research, News]
tags: [publication, announcement]
---
```

### Pages

Edit existing pages or create new ones in the root directory (e.g., `about.md`).

## Configuration

Edit `_config.yml` to customize:
- Site title and tagline
- Author information
- Navigation links
- Google Analytics (optional)

## Deployment

This site is automatically deployed to GitHub Pages when you push to the `main` branch.

## Theme

This site uses the Noir theme, which features:
- Responsive, mobile-friendly design
- Automatic dark mode support
- Clean, modern typography
- Archive, categories, and tags pages

For more information about the theme, visit: https://github.com/essentialenemy/noir

## License

MIT License - see LICENSE file for details.
