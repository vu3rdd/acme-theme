# Plan 9 Acme colour theme for Emacs

A theme that tries to emulate the colour scheme in Plan 9. We eschew syntax highlighting by
means of colours and instead try to embrace typographic elements.

## Why

I am writing it mainly because I like Acme. I also like the extensibility and composability
of emacs. I like to marry the advantages of the two. Emacs already provides (by design) the
kind of extensibility provided by Acme but in a different way -- by means of emacs lisp
processes etc where as Acme embrace the filesystem approach and extensibility via any 
programming language. The thing that tilts me in favour of emacs is my own familiarity
with it and the fact that it is more keyboard oriented. While text commands can be easily
attached to Acme, it needs heavy use of mouse and chording. I am yet to find a good mouse
that can work well with acme. I have tried everything from evoluent to various gaming mice
and didn't find a good user experience. That might be a personal thing. But hey, that's why
I am writing this mode because Emacs is very easily extensible and this sounded like a way
to learn some emacs lisp, which I haven't used for a while.

## Install

It is too early at the moment. The way I use it is by creating a directory called `~/.emacs.d/themes/`
and then putting the `acme-theme.el` file there. After that, in the `~/.emacs.d/init.el`, I call
```
(add-to-list 'custom-theme-load-path "~/.emacs.d/themes")
(load-theme 'acme t)
```

![acme-mode-haskell](https://rkrishnan.org/files/acme-theme-screenshot.png)

