# [MarkDown Link Suggestions](https://marketplace.visualstudio.com/items?itemName=TomasHubelbauer.vscode-markdown-link-suggestions)

[![](https://vsmarketplacebadge.apphb.com/installs-short/TomasHubelbauer.vscode-markdown-link-suggestions.svg)](https://marketplace.visualstudio.com/items?itemName=TomasHubelbauer.vscode-markdown-link-suggestions)



Suggests workspace files and MarkDown file headers in MarkDown links.

![Screenshot](screenshot.gif)

See the [change log](CHANGELOG.md).

## Installing

Either [Click *Install* in the Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=TomasHubelbauer.vscode-markdown-link-suggestions)
or search for *markdown link suggestions* in VS Code Extensions pane.

## Running

- Run `npm run generate` first if you want to work on the link context recognizer spike
Use the VS Code *Extension* debug configuration by pressing F5.

## Testing

- Travis [![](https://api.travis-ci.org/TomasHubelbauer/vscode-markdown-link-suggestions.svg?branch=master)](https://travis-ci.org/TomasHubelbauer/vscode-markdown-link-suggestions) on Linux & macOS
- Azure CI:
  - [![](https://tomashubelbauer.visualstudio.com/VSCode/_apis/build/status/MarkDown%20Link%20Suggestions%20Windows)](https://tomashubelbauer.visualstudio.com/VSCode/_build/latest?definitionId=4) on Windows
  - [![](https://tomashubelbauer.visualstudio.com/VSCode/_apis/build/status/MarkDown%20Link%20Suggestions%20Linux)](https://tomashubelbauer.visualstudio.com/VSCode/_build/latest?definitionId=3) on Linux
  - [![](https://tomashubelbauer.visualstudio.com/VSCode/_apis/build/status/MarkDown%20Link%20Suggestions%20macOS)](https://tomashubelbauer.visualstudio.com/VSCode/_build/latest?definitionId=2) on macOS

Run tests either using VS Code *Extension Tests* debug configuration or by running a platform appropriate test command:

- `npm run test:posix`
- `npm run test:win32`

## Deploying

Deploying is not currently done on CI, instead it is manual:

## Publishing

- Run tests
- Update version
- Update changelog
- Execute `vsce publish`
