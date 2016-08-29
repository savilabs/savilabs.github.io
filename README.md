# Savi Website

The website for Savi. It is built with [Jekyll](http://jekyllrb.com),
hosted on [GitHub Pages](https://pages.github.com/), and managed with
[Siteleaf](http://www.siteleaf.com/).

## Developing

0. Install Ruby, preferably in the v2.3.x series
1. Clone the repository
2. Install the dependencies - `bundle install`
3. Start up the Jekyll server and show drafts - `jekyll serve -w -i -D`
4. Make changes
5. View the site at [http://localhost:4000/](http://localhost:4000/)

## Hosting & Deploying

The site is hosted and served via GitHub Pages. New changes get deployed
by pushing to `master` branch. Siteleaf also automatically pushes new
content.

## Plugins

The site makes use of plugins that GitHub Pages supports with Jekyll.
See the `gems:` section in `_config.yml` for the full list.

- [jekyll-seo-tag](https://github.com/jekyll/jekyll-seo-tag) - easy
  SEO-goodness in the site
- jemoji - allows for use of emojis in the content :sun_with_face:
- jekyll-sitemap - generates sitemap
- jekyll-feed - generates an Atom feed
