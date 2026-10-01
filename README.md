# Oualid Bouh — Portfolio

Personal portfolio featuring my experience, open-source contributions, and engineering work.

Built with Jekyll and [Moonwalk](https://github.com/abhinavs/moonwalk), with English and French content, dark and light themes, and a responsive layout.

## Local development

Use the Ruby version specified in `.ruby-version`.

```sh
bundle install
bundle exec jekyll serve
```

Open [localhost:4000](http://localhost:4000). French pages are available under `/fr/`.

## Content

- `_data/` — experience, contributions, skills, and translations.
- `index.md`, `contact.md`, `fr/` — page content.
- `_layouts/`, `_includes/`, `_sass/portfolio.scss` — shared layout and styling.
- `_config.yml` — site settings and social links.

## Build

```sh
bundle exec jekyll build
```

The site is generated in `_site/`. GitHub Actions checks the build on pushes and pull requests.

## Credits

Based on [Moonwalk](https://github.com/abhinavs/moonwalk). Original theme license: [MIT](LICENSE-MOONWALK.txt).
