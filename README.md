<!-- -*- mode: markdown -*- -->
Install
-------

Put `sackspace.el` into your `load-path`.
(`make compile` will give you a byte-compiled version)

Usage
-----

Just load file and bind `sack/backspace` to a key (prefably backspace ;)
`sack/hyper-sack` is available for keybinding as well.

    (require 'sackspace)
    (global-set-key (kbd "<backspace>") 'sack/backspace)
