## Haskell Pack for Emacs Live

An [Emacs Live](https://github.com/overtone/emacs-live) package wrapper for [haskell-mode](https://github.com/haskell/haskell-mode).

To use it with Emacs Live:

1. Install Haskell packages:

  ```
  cabal install happy alex ; needed but not listed as dependency
  cabal install ghc-mod structured-haskell-mode stylish-haskell
  ````

2. Clone this repo to your `~/.live-packs`:

  ```
  git clone git@github.com:neolee/haskell-pack.git ~/.live-packs/haskell-pack
  cd ~/.live-packs/haskell-pack
  git submodule init
  git submodule update
  ````

3. If your want customeize open config/haskell-conf.el and do what you want.
