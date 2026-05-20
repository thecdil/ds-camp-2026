---
title: About
layout: about
permalink: /about.html
# include CollectionBuilder info at bottom
#credits: true
# featured-image value can be one objectid for a photo object in this collection, a relative path to an image in this project, or a full url to any image. If left blank, no featured image will appear at top of About page.
about-featured-image: https://objects.lib.uidaho.edu/expforest/expforsav845.jpg
# set background-position for featured image, "center", "top", "bottom"
position: bottom
# major heading to display over featured image
heading: Digital Scholarship Camp
# paragraph text below heading in featured image
sub-heading: 
# additional padding added to the feature to increase size. Give value in em or px, e.g. "5em".
padding: 6em
# Edit the markdown on in this file to describe your collection
# Look in _includes/feature for options to easily add features to the page
---

## Digital Scholarship Camp 2026 Outline

*Digital Scholarship Camp* will be two meetings where we explore how we do digital projects in CDIL. This is intended as a basic introduction to concepts and tech via explorative learning and discussion that hopefully gets everyone thinking critically about digital scholarship and possibilities for their projects.

Day One:

- Intros
- Exploring existing projects, web literacy basics
- GitHub orientation
- Software and "development environment"

Day Two:

- Build demo collection
- Writing in markdown
- Discuss project ideas
- Exploring other digital scholarship areas

---------

## Icebreaker

- CollectionBuilder-Sheets collaborative collection
    - Explore [Digital Collections](https://www.lib.uidaho.edu/digital/), [CDIL project](https://cdil.lib.uidaho.edu/projects/), or some other repository. [Think about discovery features, search, Item pages, and URLs]
    - In our collaborative "ds-camp-2026" Sheet, add a row describing one Item you are interested in. [Spreadsheets + Metadata!]
- Intros: your name, your collection Item, academic background and interests, project idea(s), and experience with digital projects.
- See also:
    - [LIS Best Meal](https://collectionbuilder-lis.github.io/best-meal/)
    - [Digital Exhibit Lab](https://github.com/learn-static/digital-exhibit-lab)
    - [Digital Dramaturgy](https://github.com/digitaldramaturgy/digitaldramaturgy.github.io)

## Digital Scholarship at CDIL

Data: 

- [Wilderness Hearings](https://cdil.lib.uidaho.edu/wilderness-hearings/)
- Digitized/digital objects
- Metadata in Spreadsheets
- Text in Markdown

Templates:

- Iteration
- [CollectionBuilder](https://collectionbuilder.github.io/)
- [Oral History as Data](https://github.com/oralhistoryasdata/template)

Static vs. Dynamic web:

- Dynamic web = WordPress, Drupal, Omeka, other CMS. --> a piece of software that you install on your server, that you have to continuously update and maintain.
- Static web --> some files (html, css, js, images) that you put on a server.
- Static web = "maintaining files, not software".
- [Static Web Methodology as a Sustainable Approach to Digital Humanities Projects](https://journal.code4lib.org/articles/18372)

Examples:

- Devin, [Sedimentation](https://cdil.lib.uidaho.edu/sedimentation/)
- Andrew, make-believe

-------

## First Demo Collection

### On GitHub

- GitHub orientation
- [CB-Docs](https://collectionbuilder.github.io/cb-docs/)
- [CollectionBuilder-CSV](https://github.com/CollectionBuilder/collectionbuilder-csv)
- [Generate from template](https://collectionbuilder.github.io/cb-docs/docs/repository/)
- Look around repository
- Edit "README.md" (Markdown, Commit)
- Edit "_config.yml" (YAML, Commit)
    - url
    - baseurl
- [Activate GitHub Pages with Action](https://collectionbuilder.github.io/cb-docs/docs/deploy/actions/)
- View your demo site!

### On local

Try it on your local machine:

- Open VS Code
- [Git clone](https://collectionbuilder.github.io/cb-docs/docs/repository/clone/) using VS Code (can also use GitHub Desktop or terminal). Choose a location that is not synced to a cloud service (OneDrive, Drive, DropBox, etc)!
- Orientation to VS Code (check settings and extensions)
- Open Terminal in VS Code (check terminal set up on windows)
- `bundle install`
- `bundle exec jekyll s`
- Ctrl + C

Orientation to development environment:

- Git
- (GitHub Desktop, optional)
- VS Code
- Ruby
- Jekyll
- CollectionBuilder

-------------

## Second Demo Collection

### On local

Add new data and explore:

- Download demo data: 
    - [psychiana_cbdemo_csv.csv]({{ '/objects/psychiana_cbdemo_csv.csv' | relative_url }})
    - [sbw.csv]({{ '/objects/sbw.csv' | relative_url }})
    - [postcards.csv]({{ '/objects/postcards.csv' | relative_url }})
- Add file to repository "_data"
- Edit "_config.yml"
    - metadata
    - noindex
    - title, etc
- `bundle exec jekyll s`
- Configure stuff ([theme.yml](https://collectionbuilder.github.io/cb-docs/docs/theme/), [configs](https://collectionbuilder.github.io/cb-docs/docs/customization/))! Mess around!

Version control:

- Commit.
- Push.
- cb-docs [Commit & Push](https://collectionbuilder.github.io/cb-docs/docs/repository/commit/#commit--push-changes)
- [Get Git!](https://evanwill.github.io/get-git-b/)

## Writing in markdown

Introduction to narrative writing using markdown and includes in demo collection.

- writing on the web concepts (headings, shorter, links, media)
- markdown concepts ([Write Markdown Everywhere](https://evanwill.github.io/markdown-everywhere/))
- markdown details
- using includes
- [Add a page](https://collectionbuilder.github.io/cb-docs/docs/pages/)

## Computation concepts with Liquid

Introduction to fundamentals of computation as represented in Liquid to create basic features in CB (create and display a list of filtered items). 

- Liquid intro
- Liquid variables
- Liquid for loop
- Liquid conditionals

## Working with Spreadsheets

Introduction to CSVs, Sheets, and the data used in CB.

## Working with Files

- extensions
- filenaming
- formats
- sizes, preservation

## Working with AI

- VS Code Copilot
