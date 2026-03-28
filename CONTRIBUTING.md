# Contributing to Nodestream

Thank you for your interest in contributing to the Nodestream project.

## Development Setup

1. Install Python 3.10+ and [Poetry](https://python-poetry.org/docs/#installation)
2. Clone the repository you want to contribute to
3. Install dependencies:
   ```bash
   poetry install
   ```
4. Run the test suite to confirm everything is working:
   ```bash
   poetry run pytest
   ```

## Commit Signing

All commits must be signed. See [GitHub's documentation](https://docs.github.com/en/authentication/managing-commit-signature-verification/signing-commits) for setup instructions.

## Making Changes

1. Fork the repository and create a branch from `main`
2. Make your changes with tests covering new behavior
3. Update `CHANGELOG.md` under the `[Unreleased]` section
4. Open a pull request against `main`

## Pull Request Guidelines

- Link the issue your PR addresses (e.g. `Closes #123`)
- Include a clear description of what changed and why
- Ensure all CI checks pass before requesting review
- Keep PRs focused — one logical change per PR

## Changelog

This project follows [Keep a Changelog](https://keepachangelog.com/en/1.0.0/) format. Every user-facing change (new feature, bug fix, deprecation, removal) should have a `CHANGELOG.md` entry under `[Unreleased]` in the appropriate category: `Added`, `Changed`, `Deprecated`, `Removed`, `Fixed`, or `Security`.

## Code of Conduct

This project follows the [Contributor Covenant Code of Conduct](https://github.com/nodestream-proj/nodestream/blob/main/CODE_OF_CONDUCT.md). By participating, you are expected to uphold this standard.

## Questions

For questions and discussion, use [GitHub Discussions](https://github.com/orgs/nodestream-proj/discussions).
