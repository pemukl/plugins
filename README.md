# pemukl's Claude Code plugins

One marketplace for all my Claude Code plugins. Add it once, install any of
them:

```
/plugin marketplace add pemukl/plugins
```

## Plugins

| Plugin | Install | What it does |
| ------ | ------- | ------------ |
| [bruno](https://github.com/pemukl/plugin-bruno) | `/plugin install bruno@pemukl` | Work with [Bruno](https://www.usebruno.com) API collections: write OpenCollection YAML / `.bru` requests, run them safely via the Bruno CLI with agent-friendly output. |
| [elevenlabs](https://github.com/pemukl/plugin-elevenlabs) | `/plugin install elevenlabs@pemukl` | Build and operate [ElevenLabs voice agents](https://elevenlabs.io/agents): agents, tools, workflows, testing, knowledge base, conversations, telephony — with the undocumented schema gotchas written down. |

Each plugin lives in its own repository (`pemukl/plugin-<name>`) with its own
tests, CI, and changelog — this repo only aggregates them. Every plugin repo
is also directly installable as a standalone marketplace
(`/plugin marketplace add pemukl/plugin-bruno`) if you'd rather not add this
one.

## License

[MIT](LICENSE)
