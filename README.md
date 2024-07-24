# Jekyll Website

Static website built using Jekyll. Can be deployed directly to Render, Netlify, Vercel, etc.

## System Requirements

- Ruby 3.2.0+ (Preferably installed via rvm, use `rvm use` to switch to the correct version)
- Bundler (`gem install bundler`)
- Node 18+
- Yarn (optional, but recommended)

## Setup

- `bundle install`
- `yarn install` (or `npm install`)

## Development

- `bundle exec jekyll serve`

## Build

- `JEKYLL_ENV=production bundle exec jekyll build`

This command will generate a `_site` directory with your built site.

## Deploy

- Connect the repo to [Render](https://docs.render.com/deploy-jekyll), and it will automatically deploy
  the site on every push to the main branch.
- Or you can use Netlify, Vercel, or any other hosting service that supports Jekyll building to automatically build
  and deploy the site.
- You can also manually build and deploy the contents of `_site` to any hosting service.
