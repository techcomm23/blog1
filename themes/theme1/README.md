

### Build & Test

It is necessary to have `less` and `uglifycss` installed to build and run the demo.
Assuming that already have NodeJS/NPM installed, run `npm install -g less uglifycss`.

To update or generate the minified CSS file:

```
make build
```

To build your site and test, run:

```
hugo server
```

To preview the exampleSite, run

```
make demo
```

The above command copies current state of the theme to exampleSite/themes and starts hugo with hugo serve -D (Go does not support Symlink directories)

### Disqus

Add the following line to your config, ```disqusShortname = "yourdiscussshortname"``` When this is set, all posts are disqus enabled   
You can disable comments for a post by adding the following to your page meta data: ```disable_comments: true```.



