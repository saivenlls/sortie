# sortie

Small Go tool: declutter ~/Downloads in one command

Side project, maintained when I have time.

## Installation

```bash
go build -o bin/ ./...
```

## Features

- Single static binary, no runtime deps
- Groups files into folders by extension
- Skips hidden files and folders by default
- Dry-run prints the plan before moving anything

## How to use

```bash
./bin/sortie ~/Downloads --dry-run
./bin/sortie ~/Downloads
```

## Project structure

```text
├── .github/
│   ├── workflows/
│   │   └── ci.yml
│   └── dependabot.yml
├── docs/
│   ├── configuration.md
│   ├── development.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── .gitignore
├── CHANGELOG.md
├── CONTRIBUTING.md
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

## License

MIT. Do whatever you want.
