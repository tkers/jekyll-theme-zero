# Jekyll Theme Zero

Simple [Jekyll](https://jekyllrb.com) theme for personal blog, compatible with [GitHub Pages](https://pages.github.com).

## Configuration

Add the following to your `_config.yml` file:

```yaml
remote_theme: tkers/jekyll-theme-zero
```

## Setup

1. Make sure Ruby is installed correctly
2. Install bundler if you haven't already
   ```sh
   gem install bundler
   ```
3. Then install the required gems
   ```sh
   bundle install
   ```

## Running locally

```sh
bundle exec jekyll serve
```

The blog will be served at [localhost:4000](http://localhost:4000).

## Updating github-pages gem

```sh
bundle update github-pages
```
