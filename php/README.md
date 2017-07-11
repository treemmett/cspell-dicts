# Cspell php Dictionary

Php dictionary for cspell.

This is a pre-built dictionary for use with cspell.

## Installation

Global Install and add to cspell global settings.

```sh
npm install -g cspell-dict-php
cspell-dict-php-link
```

## Uninstall from cspell

```sh
cspell-dict-php-unlink
```

## Manual Installation

The `cspell-ext.json` file in this package should be added to the import section in your cspell.json file.
```json
{
    // …
    "import": ["<path to node>/cspell-dict-php/cspell-ext.json"],
    // …
}
```

## Building

Building is only necessary if you want to modify the contents of the dictionary.  Note: Building will take a few minutes for large files.

```sh
npm run build
```

## License

MIT