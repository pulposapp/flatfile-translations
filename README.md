# Pulpos Flatfile Import Translations

In this repository we are storing our translation overrides for any import flows that are built with Flatfile.

You can read more about how to override translations for Flatfile [here](https://flatfile.com/docs/guides/localization).

## Scopes

Given we are using Flatfile for more than one import we are splitting the files into "scopes" that later have to be referenced in the app.

For example, a translation file has the following path inside the repository: `{scope}/locales/lang/translation.json`.

Whenever you want to pass this path to Flatfile you must add the correct scope & language you are trying to use.

## Why a public repo?

Flatfile needs a public URL pointing to a JSON file with all the translation overrides that we want to do.

There were several options for hosting these files, but creating a public repo in the Pulpos-App organization was the most straight forward.
