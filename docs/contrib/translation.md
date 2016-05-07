# Translations

Translations are greatly appreciated.

Localization property files are found in `ugs-core/src/resources`.

* Start with `MessagesBundle.properties`
* Rename to `MessagesBundle_<locale>.properties`
* Translate the file.

If you want to stop here, create a pull request and provide this file. I'm more
than happy to do the last steps.

To finish the job completely you'll need to know how to use [git](https://git-scm.com).

* Add your new file to `ugs-core/src/resources`.
* Open `src/com/willwinder/universalgcodesender/i18n/AvailableLanguages.java`
* Add your new translation to the `availableLanguages` object.
* [Create a GitHub pull request](https://help.github.com/articles/using-pull-requests/).