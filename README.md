# 37335

First, read the [Renovate minimal reproduction instructions](https://github.com/renovatebot/renovate/blob/main/docs/development/minimal-reproductions.md).

Then replace the current `h1` with the Renovate Issue/Discussion number.

## Current behavior

Renovate updates prettier and in doing so loses the dependencies from vue-final-modal and style-dictionary in the package-lock.json making it invalid and out of sync with the package.json.

## Expected behavior

Renovate updates prettier and both package.json and package-lock.json are valid.

## Link to the Renovate issue or Discussion

https://github.com/renovatebot/renovate/discussions/37335
