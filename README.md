<img src="https://img.shields.io/npm/v/quasar-app-extension-qui.svg?label=quasar-app-extension-qui">

Compatible with:

- Quasar UI v2 and Vue 3
- Quasar CLI with Vite v1.5+ and v2
- Quasar CLI with Webpack v3.10+ and v4

# Structure

- [/app-extension](app-extension) - App Extension for Quasar CLI
- [/playground](playground) - collection of playground apps to test the UI and App Extension

# Development

```bash
$ pnpm i # install the dependencies

$ pnpm build # build the app-extension. Run this after making any change in ./app-extension

$ pnpm dev:vite # start the app-vite playground
$ pnpm dev:webpack # start the app-webpack playground
```

For more development-related explanation, see:
- [`app-extension/src/runtime/README.md`](app-extension/src/runtime/README.md)
- [`app-extension/src/templates/README.md`](app-extension/src/templates/README.md)

# Donate

If you appreciate the work that went into this project, please consider [donating to Quasar](https://donate.quasar.dev).

# License

MIT (c) Raymond <raymondsugiarto@gmail.com>
