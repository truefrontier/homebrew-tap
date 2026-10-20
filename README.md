# truefrontier/homebrew-tap

Homebrew tap for [True Frontier](https://github.com/truefrontier) command-line tools.

## webcli / llmcli

Agent-native CLIs over your own signed-in, hidden Chrome sessions.

```sh
brew install truefrontier/tap/webcli
```

This installs both the `webcli` and `llmcli` commands (the PyPI distribution is
[`truefrontier-webcli`](https://pypi.org/project/truefrontier-webcli/); the commands keep the short names).

`webcli` and `llmcli` drive your installed **Google Chrome** (Playwright `channel="chrome"`); install
Chrome if you don't have it. This formula does not download Playwright's own browser binaries — see
`brew info webcli` caveats. Sign in once per identity with `webcli identity login <provider>:default`
(opens a visible window; run it yourself). Data home is `~/.webcli`.

See the project: https://github.com/truefrontier/webcli
