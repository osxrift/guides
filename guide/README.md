# OSX Rift's guide repository
This repository contains all the text from [OSX Rift's Guides](http://osxrift.com/guides). Feel free to fork and [contribute](contribute.md)!

## Content
All content on this site is written in Markdown with YAML front matter.

### Frontmatter
The frontmatter helps describe the page and render different components outside the scope of the page.

#### Breadcrumbs
Breadcrumbs are the the links beside the big blue "GUIDE" at the tops of the page. The describe the path to the current guide. They are order top down, first is the start of the breadcrumbs and last is the current page.

	breadcrumbs:
	  - link: /guide/getting-started # relative link to guide
	    title: Getting started
