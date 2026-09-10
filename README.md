# flockr-v2

Small Go tool: declutter ~/Downloads in one command

Small but I use it weekly.

## Examples

```bash
./bin/flockr-v2 ~/Downloads --dry-run
./bin/flockr-v2 ~/Downloads
```

## Highlights

- Skips hidden files and folders by default
- Groups files into folders by extension
- Single static binary, no runtime deps
- Dry-run prints the plan before moving anything

## Install

```bash
go build -o bin/ ./...
```

## Project structure

```text
├── .github/
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── configuration.md
│   ├── development.md
│   └── usage.md
├── .gitignore
├── CHANGELOG.md
├── LICENSE
├── SECURITY.md
├── go.mod
└── main.go
```

## Development

```bash
go build ./...
go vet ./...
```

## Why

Needed this for myself; figured others might too.

## License

MIT. Do whatever you want.
