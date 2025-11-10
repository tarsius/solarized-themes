> [!IMPORTANT]
> This fork is mostly intended for my own use.

# A fork of a port of Solarized to Emacs

This is a fork of [`solarized-theme`][e], which in turn is a port of the
[original][v] implementation for Vim.  The Vim implementation was developed
by Ethan Schoonover, the upstream Emacs implementation by Bozhidar Batsov
and Thomas Frössman.

At least two more implementations for Emacs exist, the [original port][o]
by Greg Pfeil and [another][a] by Steve Purcell.

I forked because I disagreed with the [decision][y] to massively refactor,
in order to define many more non-solarized themes within the same package,
a move that immediately broke the actual Solarized themes.  No doubt that
has been fixed by now, but in the turmoil that followed, I also realized
that Solarized was good enough as-is, and that I was no longer benefiting
from third-party contributions.  It seems more productive to just tweak
it a bit myself, if and when I see the need, and otherwise skip the churn.

[v]: https://ethanschoonover.com/solarized/
[e]: https://github.com/bbatsov/solarized-emacs/
[o]: https://github.com/sellout/emacs-color-theme-solarized/
[a]: https://github.com/purcell/color-theme-sanityinc-solarized/
[y]: https://github.com/bbatsov/solarized-emacs/issues/354/
