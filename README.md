# Sometimes you need to package up a web component

when you do, this has rollup

## intentionally inadequate instructions:

Too lazy to write this in a more literally correct way, so here's the contextually inadequate version

- search for "fix" and change all `fixme` and `fix-me` and `FixMe` etc to whatever is appropriate for your instance
- add whatever code you need need to your new web component
- `npm run build` and then `npm start` to keep testing your wc until you think it is ready for external deployment
- then set your envirnment variable `export FIXME ../somewhere/wherever` to point to the final destination you wish to deploy it to
- `npm run build` will then deploy to this location
