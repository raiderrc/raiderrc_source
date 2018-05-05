# Overview

This is the source code for raiderrc.com. The compiled source is hosted through Github Pages at https://github.com/RaiderRCStream/RaiderRCStream.github.io.
The uncompiled middleman project code is hosted at https://github.com/raiderrc/raiderrc_source

## Building

```
bundle install
bundle exec middleman
```

## Deploying
Ensure you have a git remote called "page" pointed at https://github.com/RaiderRCStream/RaiderRCStream.github.io

Then: `bundle exec middleman deploy`


## Committing

Ensure you have remote `origin` pointed to https://github.com/raiderrc/raiderrc_source

Most changes should happen in `index.html.erb` or `site.css.scss`. Commit as usual and `git push origin master`.
