# homebrew-tap

Homebrew tap for [Ghostties](https://ghostties.org/), a terminal with a multi-agent workspace sidebar, built on [Ghostty](https://github.com/ghostty-org/ghostty).

## Install

```
brew install --cask seansmithworks/tap/ghostties
```

Apple silicon only, macOS 13 (Ventura) or later.

After install, the app self-updates via Sparkle — that's why the cask sets `auto_updates true`, so Homebrew won't try to manage version bumps itself.

## Source

The cask in this tap is generated from `dist/ghostties/homebrew/ghostties.rb` in [SeanSmithWorks/ghostties](https://github.com/SeanSmithWorks/ghostties) and synced here. Edit it there, not in this repo.

Main repo: https://github.com/SeanSmithWorks/ghostties
Site: https://ghostties.org/
