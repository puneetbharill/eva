# EVA - a CRISPR story website


## Build CSS

  $ sass styles/scss/main.scss static/styles/main.css


## Deployment

1. run `hugo` to build the page
2. checkout `gh-pages` branch
3. `cp -r public/* .` to copy build files from `public` into the root dir
4. `git push origin gh-pages`



## Thanks

Design based on the [hugo Osprey theme](https://themes.gohugo.io/osprey/) by [Toma Nistor](https://tomanistor.com/) - thanks!
