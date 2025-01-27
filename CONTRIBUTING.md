# Contributing to awsrun / azurerun

Thank you for contributing to awsrun / azurerun! This guide will help you get started and know what to expect. All contributions and project spaces are subject to our [Code of Conduct](https://github.com/fidelity/.github/blob/main/CODE_OF_CONDUCT.md).

We welcome all types of contributions, including:

- Code contributions
- Bug reports
- Responsibly disclosed security concerns
- Documentation fixes
- Feature requests and user stories (although we can't guarantee we'll get to all requests, it's helpful to know where we can improve)

If you have any questions, please contact [opensource@fidelity.com](mailto:opensource@fidelity.com).

## How to report a bug?

Please [open an issue](https://github.com/fidelity/awsrun/issues) **unless** you are making a significant security disclosure.

When reporting a bug, please start from a fresh pull of the default branch and document how you encountered the issue. Reports with insufficient detail and which we can't reproduce may be closed without action.

While bugs can be frustrating, we ask participants to contribute positively and professionally to the discourse. While we commit to take the contents of the report seriously, abusive behavior be will not be tolerated.

## How to disclose security concerns responsibly?

Please follow the instructions in our [security policy](https://github.com/fidelity/.github/blob/main/SECURITY.md) (also visible in the Security tab on the project's repo).

## How to request features or submit a user story?

To request a feature please open an issue and tag it as `feature enhancement`. If you already have an implementation, please [link the pull request to the issue](https://docs.github.com/en/issues/tracking-your-work-with-issues/linking-a-pull-request-to-an-issue#linking-a-pull-request-to-an-issue-using-a-keyword).

Please include as much information and context as you can. Understanding how the feature solves a specific problem will help us prioritize the request. Please understand that we will not be able to provide an implementation timeline on all requests, although requests that include an implementation are more likely to land sooner.

If you won't do the work yourself, please also add a `good first issue` or `help wanted` label. These are special issue tags which are intended to help new and existing contributors get involved in a meaningful and accessible way.

- `good first issue` - Small changes that are suitable for a beginner
- `help wanted` - More involved changes This will help match your request with others who are looking for a way to get involved.

## How to contribute code?

Code contributions are welcome in all of our projects as long as you follow a few rules:

- Your contribution must be received under the project's open source license.
- You must have permission to make the contribution. We strongly recommend including a Signed-off-by line to indicate your adherence to the [Developer Certificate of Origin](https://developercertificate.org/).
- All code contributions must be made via PR, and all checks must pass before merging.
- All code must be formatted using [black](https://github.com/psf/black).
- PR titles and commit messages must follow [Conventional Commits Specification](https://www.conventionalcommits.org/): `<type>[optional scope]: <description>`
  - The following types can be used: `feat`, `fix`, `docs`, `style`, `refactor`, `perf`, `test`, `build`, `ci`, `chore`, or `revert`. Refer to the [Conventional Commit Cheatsheet](https://kapeli.com/cheat_sheets/Conventional_Commits.docset/Contents/Resources/Documents/index) for when to use each type. For example, `feat: add sso credential plugin`.
  - The optional scope should be used if the changes are limited to a single module or command. For example, if adding the ability to filter events in the awsrun `last` command: `feat(last): add event filtering`.
  - If there are breaking changes in the commit/PR, then you must include an `!` immediately before the `:`. For example, `fix!: change environment variable name` or `feat(last)!: use regexps for filter specification`.

While not strictly necessary, we encourage you to open an issue prior to your pull request to let the project know to expect your code. This helps the team plan for the next release and may result in your feature being a higher priority, and also decreases the likelihood of two independent contributions that do the same thing.

## How to contibute documentation fixes?

Minor documentation fixes can be submitted directly as a pull request without filing an issue in advance. More significant changes (e.g., refactoring to support a new documentation format, major reorganizations of content, etc.) should first be discussed in an issue to ensure everyone's time is used effectively. All PR titles and commit messages for documentation changes should be in the format of `docs: <message>` per Conventional Commits specification.

When opening a PR or issue with a documentation change, please add a `documentation` label.

## Getting started (and helping others find their footing)

Anyone may open an issue and apply a `good first issue` or `help wanted` label for others to work on. We only ask that when someone else picks up your issue and decides to work on it that you be responsive to their questions.

## Getting help

If you have other questions about this project, please [open an issue](https://github.com/fidelity/awsrun/issues). To reach the Fidelity OSPO directly, please email [opensource@fidelity.com](mailto:opensource@fidelity.com).
