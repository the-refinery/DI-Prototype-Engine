# D-I Prototyping Engine

This repository acts as a base starting application for quick UI prototypes.  It currently uses a few D-I staples:

- Normalize CSS
- Ember

The application is bootstrapped with Yeoman, and served using Grunt.

## Setting Up

After cloning the repository, run:

`npm install & bower install`

There, you're all setup.

To run the application on localhost:9000 use:

`grunt server`

## Getting Started with your Prototype

You only need to know a few basic concepts to get started:

- You'll need to setup a route for each page in your prototype in app/scripts/main.js
- Your pages are .handlebars files in app/templates with the same name as your route.
- Use the [link-to](http://emberjs.com/guides/templates/links/) handlebars helper to link between pages.