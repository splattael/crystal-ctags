ctags-crystal
=============

[Universal CTags](http://ctags.io) (former [Exuberant CTags](http://ctags.sourceforge.net/)) support for the [Crystal The Programming Language](http://crystal-lang.org/) language.

This means that if you are writing your Crystal code using an editor
that supports ctags (e.g.  Vim, Emacs, Sublime Text, and many others), you
can easily jump to the definition of any symbol.  Handy for navigating 
your way around a large, unfamiliar source tree.

To enable
---------

Copy or append this `.ctags` file to your own `~/.ctags`.

    $ curl https://raw.githubusercontent.com/splattael/crystal-ctags/master/.ctags >> ~/.ctags

Once you have done that, you can build tags for an Crystal app with the usual
ctags command line: cd into your project, and then

    $ ctags -R .

Feedback
--------

As a Crystal *and* ctags newbie feedback is very much appreciated.

Credits
-------

This document is based on [mmorearty's](https://github.com/mmorearty) [elixir-ctags](https://github.com/mmorearty/elixir-ctags).
