# phpcs-rules

An opinionated ruleset for phpcs.

## Usage

Installation via composer: \
``composer require --dev oneserv/phpcs-rules``

You also have to set the `phpcodesniffer-search-depth` to at least 5.

To achieve this add the following snippet to the `extra` section in your `composer.json`:

```JSON
{
  "extra": {
    "phpcodesniffer-search-depth": 5
  }
}
```
