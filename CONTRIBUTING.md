# Contributing

Thanks for helping improve this GitHub profile README. This repository is the special `username/username` repo that GitHub renders on [github.com/paridhijsingh](https://github.com/paridhijsingh). There is no application code, package, or test suite — almost every change is Markdown.

Please read the [Code of Conduct](CODE_OF_CONDUCT.md) before opening an issue or pull request.

## Ways to contribute

Useful contributions include:

- Fixing typos, broken links, or outdated project descriptions
- Improving accessibility (alt text, heading order, contrast in badges)
- Suggesting a clearer section layout or a project that should be featured
- Reporting widgets or images that fail to load

Please do **not** use issues or pull requests for job inquiries, recruiting, or general AI questions. Use [SUPPORT.md](SUPPORT.md) instead.

## Local setup

You only need Git and a Markdown previewer (GitHub's own preview is enough).

1. Fork the repository and clone your fork:

   ```bash
   git clone https://github.com/<your-username>/paridhijsingh.git
   cd paridhijsingh
   ```

2. Create a branch named after the change:

   ```bash
   git checkout -b fix/broken-portfolio-link
   ```

3. Edit `README.md` (and community files under `.github/` if needed).

4. Preview the Markdown on GitHub after you push, or in your editor. Profile READMEs render from the default branch (`main`).

## Style guidelines

- Keep the README scannable: short paragraphs, tables or lists for projects, `<details>` for optional content.
- Prefer GitHub-Flavored Markdown. Use relative links for files in this repo (`CONTRIBUTING.md`, `LICENSE`) and absolute HTTPS links for everything else.
- Do not invent experience, employers, or project claims. If a fact is uncertain, open an issue first.
- Do not add analytics, visitor counters, or third-party widgets unless they degrade gracefully and include alt text.
- Leave community health files (Code of Conduct, Security, templates) in their current locations so GitHub continues to detect them.

There is no linter or test runner in this repository. Before you open a pull request:

- Click every link you added or changed
- Confirm images and stats widgets load while signed out
- Keep the README well under 500 lines

## Pull request process

1. Open a pull request against `main`.
2. Fill in the pull request template: what changed, why, and which issue it closes (`Closes #123`).
3. Keep the change focused. A typo fix and a full README redesign should not share a PR.
4. Expect review from `@paridhijsingh`. Small, factual fixes are usually merged quickly.

## Issue labels

When labels exist, use them as follows:

| Label | Meaning |
| --- | --- |
| `bug` | Something on the profile is wrong or broken (link, image, fact) |
| `enhancement` | A proposed improvement to the README or community files |
| `triage` | Newly opened; not yet reviewed |

Security issues are **not** filed as public issues. See [SECURITY.md](SECURITY.md).
