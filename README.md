# Visiosto Prettier Configuration

[![Main workflow](https://github.com/visiosto/prettier-config/actions/workflows/main.yml/badge.svg)](https://github.com/visiosto/prettier-config/actions/workflows/main.yml)

These are the Prettier configurations for Visiosto projects.

## Installation

First install [Prettier](https://prettier.io) and the configuration package.
Please note that the `@visiosto/prettier-config` package is stored within the
GitHub npm package registry. To get the package from the right registry, add
`@visiosto:registry=https://npm.pkg.github.com` to your `.npmrc`.

    npm install --save-dev prettier @visiosto/prettier-config

Then use the configuration object in your Prettier configuration. You can, for
example, export the configuration as a string in your `.prettierrc.json`.

    "@visiosto/prettier-config"

For more information on shared Prettier configuration, please see
[the Prettier documentation](https://prettier.io/docs/en/configuration#sharing-configurations).

## Licence

This project is licensed under the BSD 3-Clause License. For more information,
please see the [LICENSE](LICENSE) file.
