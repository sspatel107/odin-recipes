# Odin Recipes

A simple, multi-page static recipe website built as **Project: Recipes** from
[The Odin Project](https://www.theodinproject.com/) Foundations course. It
showcases a small collection of popular Indian recipes.

## Features

- A home page (`index.html`) that lists every recipe with a thumbnail image and links to its page.
- Individual recipe pages, each with a photo, a short description, an ingredient list, and step-by-step instructions.
- Clean, semantic HTML5 with relative links between pages.

## Recipes

- [Butter Chicken](recipes/butter-chicken.html)
- [Idli Sambar](recipes/idli-sambar.html)
- [Aloo Paratha](recipes/aloo-paratha.html)

## Skills practiced

- HTML5 document structure
- Headings, lists (ordered + unordered), links, and images
- Organizing files and folders in a small project
- Git + GitHub workflow (commit early and often)

## Project structure

```text
odin-recipes/
├── index.html
├── README.md
├── images/
│   ├── butter-chicken.jpg
│   ├── idli-sambar.jpg
│   └── aloo-paratha.jpg
└── recipes/
    ├── butter-chicken.html
    ├── idli-sambar.html
    └── aloo-paratha.html
```

### Why this structure?

- `index.html` lives in the root so it is easy to open and acts as the entry point.
- All recipe pages live inside the `recipes/` folder to keep things organized.
- Images are kept together in the `images/` folder and referenced with relative paths.

## Getting started

No build step or dependencies are required — it is plain HTML.

1. Clone or download this repository.
2. Open `index.html` in any web browser.
3. Click a recipe to view its page, and use the "Back to Home" link to return.
