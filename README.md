
# Personal Website
This is the repository for my personal site and blog. It is currently published via the new [Cloudflare Pages](https://pages.cloudflare.com) product. 

## Running in development
Change into this directory and run `gatsby develop`.

## Publishing a new post
This blog will render and publish any markdown file that is put in the `content` directory. The `pages` directory is for different static pages used on the site, while the `posts` directory is for actual blog posts. For post formatting, just append the following header chunk to any markdown document:

```
---
title: // the post title
date: // the published date
template: 'post'
draft: false // set this to false for it to be live
slug: // something catchy
category: // used for site categorization
tags:
  - // list
  - // like
  - // this
description: // short description used for certain embeds 
---
```
Note that you should remove the H1 header (a single # in Markdown) from your post before you append the header, otherwise the post looks weird