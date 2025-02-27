# SSPP Lawn Fete Hugo Static Website

This is a Hugo-based website for a SSPP Lawn Fete event.

## Project Structure

The site is built using the following structure:

- `assets/`: Contains images that are intended to be scaled or altered on build, javascript, css
- `content/`: Contains the Markdown files for each page
- `data/`: Contains YAML files for features and schedule
- `layouts/`: Contains HTML templates for the site
- `static/`: Contains static assets like images that should not change
- `config.toml`: Main configuration file

## Color Scheme

- Pale Yellow: #e5e08c
- Coral: #f18062
- Brick Red: #b44040
- Light Teal: #91ede3
- Teal: #2bd0ce

## Getting Started

1. Install Hugo (https://gohugo.io/getting-started/installing/)
2. Clone this repository
3. Run `hugo server` to start the development server
4. Visit http://localhost:1313 to view the site

## Customization

- Update event details in `config.toml`
- Modify the content of pages in the `content/` directory
- Change features and schedule in the `data/` directory
- Add custom CSS to `assets/css/main.css`

## Deployment

Run `hugo` to build the site. The generated files will be in the `public/` directory, which can be deployed to any web server or hosting service.

Currently this is configured to use Netlify for hosting (see `netlify.toml`).
