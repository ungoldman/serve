# @ungoldman/serve

```
npx @ungoldman/serve
```

## Note ⚠️

This is a fork of [vercel/serve](https://github.com/vercel/serve) published under a different namespace (`@ungoldman/serve`).

The fork was created because I needed a version of serve that opens the URL it serves, and the maintainers of serve have stuck with the decision to not do that (see https://github.com/vercel/serve/issues/116, https://github.com/vercel/serve/issues/425, https://github.com/vercel/serve/issues/454, https://github.com/vercel/serve/issues/588).

## Differences between this and [vercel/serve](https://github.com/vercel/serve)

- Opens the URL on start by default
- Adds a `--no-open` option to disable this behavior
- That's it

I'll make an effort to keep this in sync with upstream, but... no promises!

See serve's [documentation](https://github.com/ungoldman/serve#usage) for extended installation & usage info.

## License

MIT Licensed by Vercel. All credit goes to original authors/maintainers.
