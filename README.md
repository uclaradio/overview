# UCLA Radio Technology Overview

Hi! You're probably wondering what this repo is—it serves to introduce our new interns to all of the various UCLA Radio Web projects as well as give us (the Web team) an place to plan and organize the interactions between all of our various projects.

## Projects

UCLA Radio Web projects can be split into 3 categories: user-facing, internal tools, and development tools.

### User-facing Products

Our user-facing products consist of a web and native mobile apps:

* [uclaradio.com](https://github.com/uclaradio/uclaradio)
* [UCLA Radio iOS app](https://github.com/uclaradio/uclaradio-iOS)
* [UCLA Radio Android app](https://github.com/uclaradio/uclaradio-android)
* [blog.uclaradio.com](https://github.com/uclaradio/uclaradio-tumblr-theme)

### Internals Tools

Our current internal tools are:

* [Panel](https://github.com/uclaradio/panel), a site for managing internal Radio knowledge and shows.
* [Programming Scheduler](https://github.com/uclaradio/ProgScheduler), a Python script for assisting in determining show times.
* [Rivendell Scrobbler](https://github.com/uclaradio/RivendellScrobbler), a scrobbler for UCLA Radio's automation software, Rivendell.

### Developer Tools

Our developer tools are made for and used by us to make making the above projects easier. They are:

* [eslint-config-uclaradio](https://github.com/uclaradio/eslint-config-uclaradio)
* [stylelint-config-uclaradio](https://github.com/uclaradio/stylelint-config-uclaradio)

## Architecture

Our biggest projects, uclaradio.com, Panel, and our mobile apps all work together with our Shoutcast instance in order to fetch content. Here's a diagram of how it works:
![alt text](/architecture.png)
