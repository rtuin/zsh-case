# ZSH plugin to change case

This plugin adds two commands to change the casing of output:

* `tolower`
* `toupper`

These are basically aliases for `tr '[:upper:]' [:lower:]`.

## Example usage

```bash
echo "Foo" | tolower
# foo

echo "Foo" | toupper
# FOO
```

## Installation

I recommend [Antigen](https://github.com/zsh-users/antigen) to install and manage your ZSH plugins.

### Antigen

Put the following in your `~/.zshrc`:

```bash
antigen bundle rtuin/zsh-case
```