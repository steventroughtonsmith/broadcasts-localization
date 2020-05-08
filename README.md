### broadcasts-localization

This is the community language repository for [Broadcasts](https://apps.apple.com/us/app/broadcasts/id1469995354?ls=1).

If there is a language you'd like to see Broadcasts localized to but we haven't got around to it yet, and you have some git-fu, feel free to submit a pull request to the repository.

Please do not add multiple languages in the same pull request — this way, there can be a discussion thread for each language for any changes or tweaks that need to be made, and give others opportunity for peer review.

### Disk Structure
Languages are structured in folders as such:

`en.lproj/Localizable.strings`

Where `en` is replaced by the [ISO 639-1 two-letter language code](https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes), and the `Localizable.strings` file is structured as per the English (`en`) version.

Please do not include any other files in a pull request.

### Localization

Strings are denoted as `"KEY"` = `"value"`, where the keys remain the same across all languages, and the values are localized. There must be a `;` at the end of each line.

`"SEARCH_PLACEHOLDER" = "Search";`

Where you see a `%@` or `%ld` token, this denotes a value that is replaced at runtime — in most cases will be the user-provided name for a station or collection, or a number. The corresponding localized value must keep the token in the right place to provide the same meaning as the English value.

`"IMPORT_TITLE" = "Import \"%@\"?";`

`"IMPORT_BODY" = "This shared collection contains %ld stations.";`


### Credits

Please append the name you would like to be credited by to the pull request or the comment block at the top of the Localizable.strings file.