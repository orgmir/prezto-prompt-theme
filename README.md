Prezto prompt theme
===================

I've made the switch from `oh-my-zsh` to `prezto` but I missed the default `robbyrussell` theme.

This is a close aproximation of that!

Like `prezto` prompt themes states:

> A prompt theme is an autoloadable function file with a special name, `prompt_name_setup`, placed anywhere in `$fpath`, but for the purpose of this project, themes should be placed in the modules/prompt/functions directory.

So to use this, just copy `prompt_orgmir_setup` to anywhere in `$fpath` and then add the following to `zpreztorc`:

```
zstyle ':prezto:module:prompt' theme 'orgmir'
```
