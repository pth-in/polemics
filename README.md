# Polemics

A Jekyll blog for critical analysis of historical and scientific claims, hosted on GitHub Pages.

## Setup Instructions

### 1. Create GitHub Repository

1. Create a new repository on GitHub (e.g., `polemics`)
2. If using username.github.io format, name it `yourusername.github.io`
3. Clone the repository locally

### 2. Install Jekyll

```bash
# Install Ruby (if not already installed)
# On Windows, use RubyInstaller: https://rubyinstaller.org/

# Install Jekyll and Bundler
gem install jekyll bundler

# Install dependencies
bundle install
```

### 3. Configure

1. Edit `_config.yml`:
   - Update `url` with your GitHub username or repository name
   - Update `author` information
   - Adjust other settings as needed

### 4. Run Locally

```bash
bundle exec jekyll serve
```

Visit `http://localhost:4000` to preview your site.

### 5. Deploy to GitHub Pages

1. Push your code to GitHub:
```bash
git add .
git commit -m "Initial blog setup"
git push origin main
```

2. Enable GitHub Pages:
   - Go to repository Settings → Pages
   - Select source branch (usually `main` or `gh-pages`)
   - Your site will be available at `https://yourusername.github.io/repository-name`

## Adding New Posts

1. Create a new file in `_posts/` directory
2. Name it: `YYYY-MM-DD-post-title.md`
3. Add front matter:
```yaml
---
layout: post
title: "Your Post Title"
date: YYYY-MM-DD
author: "Your Name"
tags: [tag1, tag2, tag3]
excerpt: "Brief description of the post"
---
```

4. Write your content in Markdown

## Customization

- **Styling**: Edit `assets/css/main.css`
- **Layout**: Modify files in `_layouts/`
- **Configuration**: Update `_config.yml`

## License

This blog template is open source. Feel free to use and modify as needed.

## Contributing

If you find errors or have suggestions for improvements, please open an issue or submit a pull request.

