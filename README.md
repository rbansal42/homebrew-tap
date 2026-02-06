# Homebrew Tap for bb CLI

Unofficial CLI for Bitbucket Cloud - like GitHub's `gh` but for Bitbucket.

## Installation

```bash
brew install rbansal42/tap/bb
```

Or add the tap first:

```bash
brew tap rbansal42/tap
brew install bb
```

## Update

```bash
brew upgrade bb
```

## Usage

```bash
# Authenticate
bb auth login

# List pull requests
bb pr list

# Create a pull request
bb pr create --title "My PR" --source feature-branch

# View repository
bb repo view
```

## More Information

- [GitHub Repository](https://github.com/rbansal42/bitbucket-cli)
- [Documentation](https://github.com/rbansal42/bitbucket-cli#readme)
- [Releases](https://github.com/rbansal42/bitbucket-cli/releases)
