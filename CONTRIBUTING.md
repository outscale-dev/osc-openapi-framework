## How to submit a contribution

Thank you for considering contributing to osc_openapi_framework.

Potential contributions include:

- Reporting and fixing bugs.
- Requesting features.
- Adding features.
- Cleaning up the code.
- Improving the documentation.

In order to report bugs or request features, search the issue tracker to check for a duplicate.

It’s totally acceptable to create an issue when you’re unsure whether
something is a bug or not. We’ll help you figure it out.

Use the same issue tracker to report problems with the documentation.

## Pull Requests

We’ll do our best to review your pull request (or “PR” for short) quickly.

Each PR should, as much as possible, address just one issue and be self-contained. 
Smaller the set of changes in the pull request is, the quicker it can be reviewed and 
merged - if you have ten small, unrelated changes, then go ahead and submit ten PRs.

Make sure to run tests/run.sh before each PR.

## How to release

- Update version in:
  - [VERSION](VERSION)
  - [README.md](README.md)
- Push PR, validate changes and merge into `master` branch
- Push corresponding tag
- Tag and push branch
- Create release
- Add `dist/osc_openapi_framework-x.x.x-py3-none-any.whl` and `osc_openapi_framework-x.x.x.tar.gz` files to release.
- Github action should have pushed packages on pip.
