# homebrew-rootout

Homebrew tap for [rootout](https://github.com/shiva2021/rootout): uninstall macOS apps completely and scan VS Code-family extensions for malicious behaviour.

```bash
brew tap shiva2021/rootout
brew trust shiva2021/rootout   # Homebrew 7 asks this once for third-party casks
brew install --cask rootout
```

The cask is rewritten by GoReleaser on every rootout release. The binary is not code-signed; the cask clears the quarantine attribute on install.
