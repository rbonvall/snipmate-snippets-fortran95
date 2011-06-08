Snipmate.vim support for Fortran 95
===================================

This plugin provides some snippets
for writing Fortran 95 (and newer) code.

I tested this plugin against `garbas's Snipmate fork`_ and using Pathogen.
If it doesn't work with your own configuration, please let me know.

.. _garbas's Snipmate fork: https://github.com/garbas/vim-snipmate

Dependencies
------------
* Vim (of course)
* Snipmate_.

Installation
------------
If you use Pathogen_,
just clone this repository
into your ``bundle`` directory::

    cd ~/.vim/bundle
    git clone git://github.com/rbonvall/snipmate-snippets-fortran95.git

Personally,
I prefer to add bundles as submodules
of the git repository for my ``.vim`` directory (`rbonvall/dotvim`_)::

    cd ~/.vim
    git submodule add git://github.com/rbonvall/snipmate-snippets-fortran95.git bundle/snippets-fortran95
    git submodule init
    git submodule update
    git commit  -m 'Add Fortran 95 snippets to bundles as submodule'

If you don't use Pathogen
(you should!)
just drop the fortran.snippets_ file
into the ``snippets`` directory
of your Snipmate installation.

.. _Snipmate: https://github.com/garbas/vim-snipmate
.. _Pathogen: https://github.com/tpope/vim-pathogen
.. _rbonvall/dotvim: https://github.com/rbonvall/dotvim
.. _fortran.snippets: https://github.com/rbonvall/snipmate-snippets-fortran95/blob/master/snippets/fortran.snippets

Author
------
Roberto Bonvallet <rbonvall@gmail.com>

