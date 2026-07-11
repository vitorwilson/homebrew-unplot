# homebrew-unplot

Homebrew tap for [unplot](https://github.com/vitorwilson/unplot) — draw a
function by hand and recover its exact formula.

```sh
brew install --cask vitorwilson/unplot/unplot
```

The app is not code-signed, so clear the quarantine flag once after installing:

```sh
xattr -dr com.apple.quarantine /Applications/unplot.app
```

The cask is generated from a template in the unplot repo and updated
automatically on each release. Do not edit `Casks/unplot.rb` by hand.
