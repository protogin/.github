# Contributing to Protogin

Thanks for taking the time to contribute. Most Protogin repositories are
currently private, but this guide applies to any Protogin repository you
have access to, including this `.github` repository itself.

## Before you start

- Search existing issues and pull requests to avoid duplicates.
- For anything beyond a small fix, open an issue first to discuss the
  change before writing code.
- Security vulnerabilities are handled separately — see
  [SECURITY.md](SECURITY.md). Do not open a public issue for a
  vulnerability.

## Code of conduct

Participation in any Protogin repository or discussion is governed by our
[Code of Conduct](CODE_OF_CONDUCT.md). By participating, you agree to
uphold it.

## Making a change

1. Fork the repository (or create a branch, if you have write access).
2. Create a branch named after the change you're making.
3. Make your change, including tests where the repository has them.
4. Run the repository's own lint/build/test commands before opening a pull
   request — check that repository's README or `CONTRIBUTING.md` override
   (if any) for the exact commands.
5. Open a pull request using the repository's pull request template. Fill
   in every section — reviewers will ask for missing information rather
   than guess at it.
6. One pull request per logical change. Please avoid bundling unrelated
   changes together, as it makes review slower for everyone.

## Commit and PR expectations

- Write clear, descriptive commit messages that explain *why*, not just
  *what*.
- Keep pull requests focused and reasonably small.
- Do not include secrets, credentials, internal hostnames, or customer data
  in commits, issues, or pull requests, in any repository.
- Never force-push a branch that other people are reviewing or building on.

## Reporting bugs and requesting features

Use the issue templates provided in the repository you're filing against.
They ask for the information needed to reproduce a bug or evaluate a
feature request without back-and-forth.
