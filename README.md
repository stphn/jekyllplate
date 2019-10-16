# Jekyllplate

[![Dependencies](https://david-dm.org/stphn/Jekyllplate.svg)](https://david-dm.org/stphn/Jekyllplate#info=dependencies)
[![Build Status](https://travis-ci.org/stphn/jekyllplate.svg?branch=master)](https://travis-ci.org/stphn/jekyllplate)

Not just another starter-kit for static Jekyll sites

This boilerplate includes common useful gulp tasks, auto-reload with BrowserSync and ES6 modules from webpack.

**## Pre-requisites**

- [Node.js](http://nodejs.org/)
- [Ruby](https://www.ruby-lang.org)

## Installation

Make sure you ****double-checked**** the pre-requisites listed above and open your command line interface and enter the following

``` ssh
$ git clone https://github.com/stphn/jekyllplate.git
$ cd jekillplate
$ yarn install
$ yarn start
```

 et voilà

- - - -

### How to write posts

To add new post, add a file in the `_posts` directory that follows the naming convention `YYYY-MM-DD-name-of-post.md` and includes the necessary YAML front matter:

``` yaml
---
headline: "First Post Demo"
excerpt: "First Post Excerpt"
categories:
- Web
tags:
- Jekyll
- Starter Kit
---
```

- - - -

### How to create pages

Create new pages in the root directory (or pretty much any subdirectory). The filename will form part of the URL.

Pages will need [front matter](https://jekyllrb.com/docs/frontmatter/) as well, for example:

    —
    layout: default
    title: “Blog”
    meta_description: “Default Blog Meta Description”
    permalink: blog/index.html
    current_nav: blog
    —

- - - -

### How to deploy

This is automatically ready to deploy, so long as the `gulp` server has been running during development.

Built code lives in the `_site` directory.

- - - -

### Available Gulp Tasks

``` javascript
`exports.images = images;`
`exports.css = css;`
`exports.js = js;`
`exports.jekyll = jekyll;`
`exports.clean = clean;`
`exports.build = build;`
`exports.watch = watch;`
`exports.default = build;`
```

- - - -

### Thanks and credits

- [Tobias Reich](https://github.com/electerious) for his inspiring work

- - - -

### Still TODO:

*  Include Open Graph protocols
*  cleaning up
*  and probably a lot more …
