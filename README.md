# paige

A simple Hugo theme. [Try it out.](https://willfaught.com/paige)

<img src="https://github.com/willfaught/paige/raw/master/images/screenshot.png" style="width: 100%">

## Features

- Blog
- Facebook sharing support
- Google Analytics support
- Landing page
- Light color scheme
- Menu navigation
- Minimal design
- Responsive, mobile-first layout
- Sections for other kinds of content
- Single column presentation
- Social links
- Twitter sharing support

## Design

HTML metadata is embedded automatically. The HTML author is the site
author. The HTML description is the page description. The HTML keywords
is a sorted union of the page keywords, tags, and categories. Enhanced
Facebook and Twitter sharing is enabled. Google Analytics is included at
the bottom of the body, if configured. You must create favicons
yourself.

The HTML title is the page title, followed by a middle dot, followed by
the site title. If one is missing, the other is used without the middle
dot. If both are the same, only one is used without the middle dot.

The HTML body can have a header, a body, and a footer. The header has
the section menus, if any; the page title, if any; the page description,
if any; and the page date, if any. The body has the content, if any. The
footer has the copyright notice, if any.

The page date is the publish date, if it exists; otherwise, it's the
creation date.

Everything is stacked vertically in one column and aligned to the
center.

List page items are the page title with the page description underneath,
grouped by month and year, and sorted in descending order. Page list
length is configured in `config.yaml`.

The section menus in the header are activated if their section matches
the current page. Pages directly under `content` match the section path
`/`. The section menu names, paths, and order are configured in
`config.yaml`.

If a page has a `link` parameter, it's used as the reference for an
anchor around the page title, if any.

If `partials/head.html` exists in the site, it is included at the end of
the head tag. If `partials/body.html` exists in the site, it is included
at the end of the body tag.

The home page shows the `blurb`, `description`, `greeting`, and `title`
parameters from `content/_index.md`, the `avatar.png` and `cover.png`
images at the site root, and linked icons for all the social sites
configured in `config.yaml`.

Taxonomy pages are an inline, unordered, sorted list of links to terms.

The 404 page has a "Not Found" header, and no body.

An empty list has a "Nothing Here" header, and no body.

Stock Bootstrap 5.2.2 and Bootstrap Icons 1.10.2 are used for style and
icons. They're loaded from the Bootstrap CDN for every page.

## Configuration

See the example site directory for an example configuration.

## Credits

- Avatar photo by [Yuvraj Singh](https://unsplash.com/photos/ljziSm0DXg8)
- Cover photo by [Kamran Sabir](https://www.pexels.com/photo/green-lake-surrounded-by-mountain-127753/)
