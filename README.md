# Claude Code Skills Marketplace

A curated marketplace of Claude Code skills focused on software engineering best practices.

## Installation

Prefer running this command after Claude starts:

```
/plugin marketplace add https://github.com/tercel/claude-code-skills
```

Or edit `~/.config/claude/config.json`:

```json
{
  "skillMarketplaces": [
    {
      "url": "https://github.com/tercel/claude-code-skills"
    }
  ]
}
```

## Available Skills

### spec-forge

Generate professional-grade software specifications — PRD, SRS, Technical Design, and Test Plan — based on industry standards (Google, Amazon, IEEE). Works standalone or as a full traceability chain.

- **Repository**: https://github.com/tercel/spec-forge

### code-forge

Forge executable, TDD-driven implementation plans from documentation — with task breakdown, progress tracking, pause/resume, and team collaboration.

- **Repository**: https://github.com/tercel/code-forge

## Contributing

Contributions are welcome! Please feel free to submit issues or pull requests.

## License

Apache License 2.0
