# Ogle

The smallest accelerator project for rapid prototyping in browser.


## Building for production

I've included [Purgecss](https://www.purgecss.com/) and [cssnano](https://cssnano.co/) to optimize CSS for production.

To build an optimized version of your CSS, simply run:

```bash
# Using npm
npm run production

# Using Yarn
yarn run production
```

After that's done, check out `./public/build/styles.css` to see the optimized output.
