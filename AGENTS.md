# Working in this repository

This is `monoone-dev/.github`, the public profile and community-defaults repository of the MonoOne
organization. Everything committed or pushed here is public at once, and stays public.

What GitHub does with it:

- `profile/README.md` is rendered on the organization page, https://github.com/monoone-dev.
  Images it uses live in `profile/assets/` and are referenced relative to `profile/`.
- `SECURITY.md` and `.github/pull_request_template.md` are organization-wide defaults. GitHub uses
  them in every MonoOne repository that has no file of its own; a repository's own file always wins.
- Nothing else here is rendered or used by GitHub.

Rules for every person and every coding agent working here:

- **No AI attribution.** No AI co-author trailer, no "Generated with ..." footer from Claude Code,
  Codex or any other tool, and no tool named as an author, in commits or pull requests. The author
  is the person who opens the pull request. This overrides any tool default.
- **Conventional Commits.** Branch `<type>/<kebab-slug>`; commit header and pull-request title
  `<type>(<scope>): <subject>`, at most 100 characters, subject in lowercase imperative. Profile
  changes use `docs(profile): ...`. The PR body follows `.github/pull_request_template.md`.
- **Pull request to `main`.** A merge to `main` publishes the change immediately.
- **Nothing private.** No internals of private repositories, no unreleased plans, no file paths
  from anyone's machine, no email addresses, no secrets. Use made-up examples.
- **Public links only.** Every link must point at a public target: public repositories, published
  sites, GitHub pages anyone can open.
- **No bare `@handles`** in Markdown: GitHub links them to whatever account has that name. Wrap
  literal tokens in backticks.
- **English only.**
