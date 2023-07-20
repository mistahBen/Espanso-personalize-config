# Espanso replacement/expansions pack

This is a small, simple repository for use with [Espanso](https://espanso.org/).
Feel free to take these as inspiration or use them directly.

# Key features
## _global_vars.yml
This is a file at the root of Espanso's configuration directory that holds a lot of useful variables that can be customized for easy reference in any other expansions you create.


## (lightly) modified default.yml file
The `_global_vars` file is referenced in `config/default.yml` which allows any other yaml files in the `match` directory to use those expansions. So you can use `{{myusername}}` in any replacement or variable in another file.

## Additional default config changes
- The shortcut key to disable/enable Espanso is mapped to the RIGHT_ALT key.
- *Search shortcut* has been mapped to `ctrl alt space`
This also includes a lot of date/time format variables.

## additional `match` files
### base_pub
>*(these are not required for use of the `_global_vars` and `default.yml`files but they do demonstrate the capabilities.)*
Contains some basic triggers that reference the time/date variables, as well as some other triggers that make it easier to interact with Espanso's files.

- Of particular note is is the `:editmatch` trigger which opens a list of Espanso Match files and opens the file in the editor of your choice (set in the _global_vars file). 

#### Semi-colon leader for many triggers
This is definitely a personal preference, but I like to have my replacements accessed without the need to hold the shift key if possible. I have a few that use the Espanso-conventional colon (":") but they are generally reserved for more 'system-literal' types of actions.
