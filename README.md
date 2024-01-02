# Gravity Forms x Polylang

This Wordpress plugin adds form titles, descriptions, field labels, etc, to Polylang string translations

This repository is a fork of [pdme/gravity-forms-polylang](https://github.com/pdme/gravity-forms-polylang) to update the plugin to work with the latest version of wordpress and implement open pull requests of the original repository.

## Installation
### From the Wordpress plugin directory
Gravity Forms x Polylang is available on the [Wordpress plugin directory](https://wordpress.org/plugins/translate-gravity-forms-x-polylang/).

### Manual Wordpress installation
Download the latest version of the plugin from the [Releases](https://github.com/siebsie23/gravity-forms-polylang/releases) section. You can then manually upload the zip file in the "plugins" section of your wordpress installation.

### Wordpress via composer
The plugin is installable via [WordPress Packagist](https://wpackagist.org/). A site that mirrors the Wordpress plugin and theme directory as a repository for composer.
If you don't have it already, add WordPress Packagist as a repository to your composer.json file. Example:
```json
"repositories":[
        {
            "type":"composer",
            "url":"https://wpackagist.org",
            "only": [
                "wpackagist-plugin/*",
                "wpackagist-theme/*"
            ]
        }
    ],
```
And add the Gravity Forms x Polylang plugin to the requirements section. Example:
```json
"require": {
    "wpackagist-plugin/translate-gravity-forms-x-polylang": "1.0.0"
}
```
After this, run `composer update` and activate the plugin in the "plugins" section of your wordpress installation
