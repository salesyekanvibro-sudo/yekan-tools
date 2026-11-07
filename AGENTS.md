# Project conventions

## WordPress plugin naming

For every future WordPress release of this project, use this exact display-name format:

`Yekan ISO 20816 Training vX.Y.Z`

Replace `X.Y.Z` with the release version, for example `Yekan ISO 20816 Training v1.0.1`. Preserve the spelling, capitalization, and spaces of `Yekan ISO 20816 Training`.

Set the main plugin PHP header `Plugin Name` to this full display name. Set its separate `Version` header to the same numeric version without the `v` prefix. Keep the displayed release name and version consistent in release documentation.

See [docs/PROJECT.md](docs/PROJECT.md) for the project naming and versioning policy. This naming requirement does not authorize changing plugin directory names, shortcodes, or saved option keys.
