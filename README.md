# cliparse

Small TypeScript CLI: CSV to JSON converter

Started as a weekend hack, grew on me.

## Getting started

```bash
npm install
npm run build
```

## Highlights

- commander-based subcommands
- npm link friendly
- Strict tsconfig, no any
- Ships as an ESM binary

## Examples

```bash
npx . convert data.csv -d ';'
# or after npm link: cliparse convert data.csv
```

## Project structure

```text
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   └── bug_report.md
│   ├── dependabot.yml
│   └── pull_request_template.md
├── docs/
│   ├── configuration.md
│   ├── faq.md
│   └── usage.md
├── src/
│   ├── config.js
│   └── index.ts
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── SECURITY.md
├── package.json
└── tsconfig.json
```

## Why

Needed this for myself; figured others might too.

## License

MIT - see [LICENSE](LICENSE).
