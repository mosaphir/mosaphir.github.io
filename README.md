# Jekyll Curate Premium Theme

Jekyll Curate is a portfolio theme with multiple project layouts.

### Documentation

[Live Docs](https://www.zerostatic.io/docs/jekyll-curate)

### Demo

[Live Demo](https://jekyll-curate.netlify.app/)

### Screenshot

![Jekyll Curate Theme screenshot](https://www.zerostatic.io/theme/jekyll-curate/jekyll-curate-screenshot.png)

## Install

### Install Jekll

Make sure you have Ruby & Jekyll installed - For a step-by-step guide, read Jekyll docs [installation](https://jekyllrb.com/docs/installation/)

### Install Theme

Extract the theme .zip file to your local computer. Navigate to the project root (it contains the README.md)

Run `bundle install` to install gems.

Then run `jekyll serve` or `bundle exec jekyll serve` to start the Jekyll server.

To build the Jekyll site run `bundle exec jekyll build`

## Deploy

### Netlify

This theme is pre-configured to deploy with [Netlify](https://docs.netlify.com/site-deploys/create-deploys/).

> 💡 If you experience bundle install issues during the Netlify deployment, deleting the Gemfile.lock can sometimes help

### GitHub Pages

This theme works with GitHub Pages. If you are creating a GitHub Pages "Project site" then your site will be in a sub-folder ie `http://username.github.io/repository` You will need to update the `baseurl` in the `_config.yml` for the asset paths to work correctly.

```yaml
# _config.yml
baseurl: "/jekyll-curate-pro" # This should be the name of your repo
```

## Credits

This theme uses open-source libraries and assets.

- **Bootstrap 5** https://unsplash.com/license
- **Font Awesome 6 Free:** https://fontawesome.com/
- **Unsplash Images** https://unsplash.com/
