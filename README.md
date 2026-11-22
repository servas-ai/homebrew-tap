# servas.ai Homebrew tap

Homebrew formulae for the servas.ai command-line tools (macOS and Linux).

```bash
brew install servas-ai/tap/bcli
```

| Formula | What | Docs |
|---|---|---|
| `bcli` | CLI for servas.ai Browser as a Service: real, headed cloud browsers for agents and tests over CDP | [servas-ai/bcli-public](https://github.com/servas-ai/bcli-public) |

Upgrade with `brew upgrade bcli`, remove with `brew uninstall bcli`.

The formulae download the release binaries from the public release repositories and check them against the
SHA-256 values from each release's Ed25519-signed `SHA256SUMS`. The binaries are proprietary software by servas.ai;
see the license in the release repository.
