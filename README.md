# Portfolio Web Project (Work in Progress)

This repository contains my personal portfolio web project, built with **SCSS** (using partial/module files) and **semantic HTML**. The site is a work in progress: you’ll see placeholder text (lorem ipsum) and certain links are not fully set up yet.

## Overview

-   **Semantic HTML & Accessibility**  
    The HTML structure aims to follow semantic best practices. Used headings (`<h1>`, `<h2>`, etc.) to maintain a proper hierarchy, and included ARIA attributes with descriptive text to improve accessibility.

-   **SCSS with Partials**  
    The styles are organized in multiple SCSS partial files (e.g., `_palette.scss`, `_typography.scss`, `_devices.scss`). These are imported into a main `styles.scss`, which compiles down to `styles.css`.

-   **Color Contrast & Layout**  
    The site’s color palette is chosen for good contrast. Sizing is mostly in `rem` units for better scalability when the user zooms or enlarges the screen.

-   **Placeholders**  
    The content includes **lorem ipsum** text for now. Links (such as navigation items and project images) are not yet included.

## Live Demo

You can view the live site here:  
[**https://sidendev.github.io/web-project/**](https://sidendev.github.io/web-project/)

## How to Clone & View Locally

**Clone the Repo**
`git clone https://github.com/sidendev/web-project.git`

**Then change into the project folder:**
`cd web-project`

**Compile SCSS**
`npm run sass`

**Run command to watch file for changes in sass**
`sass --watch --no-source-map styles.scss css/styles.css`

**Simply open index.html in your browser, or use a local dev server such as live-server**

## Roadmap

-   Replace all lorem ipsum content with real content.
-   Add functioning links for site navigation and project images.
-   Integrate a functional contact button.
-   Further improve responsiveness (especially tablet breakpoints).
