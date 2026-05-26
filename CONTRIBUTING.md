# Contributing to H5P Repositories

Thank you for your interest in contributing to H5P! 🎉  
We’re excited to collaborate and improve H5P together. This guide explains how to contribute and what to expect.

---

## 📚 Table of Contents

- [Ways to Contribute](#-ways-to-contribute)
- [Getting Started](#-getting-started)
- [Commit Conventions](#-commit-conventions)
- [Pull Request Guidelines](#-pull-request-guidelines)
- [Reporting Issues](#-reporting-issues)
- [What to Expect](#-what-to-expect)
- [Community Values](#-community-values)
- [License](#-license)

---

## 💡 Ways to Contribute

There are many ways to help improve H5P:

- 🐞 Report bugs by opening an [issue](#-reporting-issues)
- ✨ Suggest new features or enhancements by opening an [issue](#-reporting-issues) or [pull request](#-pull-request-guidelines)
- 📖 Improve documentation (even small fixes help!)
- 🌍 Contribute translations
- 💻 Submit code changes (bug fixes, features, performance improvements)
- 👀 Review [pull requests](#-pull-request-guidelines) and provide feedback

---

## 🛠 Getting Started

1. **Fork the repository**  
   Create your own copy of the project. Unsure which repo to fork? Reach out on our [forum](https://matrix.to/#/#h5p-open-source:matrix.org)

2. **Create a branch**  
   Base all changes on the `master` branch. For branch names, we follow the following [best practices](https://dev.to/shnjd/git-good-best-practices-for-branch-naming-and-commit-messages-oj4)

3. **Make your changes**  
   Keep commits focused and meaningful. Follow the [commit conventions](#-commit-conventions).

4. **Run tests (if applicable)**  
   Ensure everything works as expected.

5. **Push and create a Pull Request**  
   Follow the [pull request guidelines](#-pull-request-guidelines).

---

## ❗ Commit Conventions

Please follow this format for commit messages:

```text
category / message
```

Example:

```text
feature / Add hint button
```

For more details, see [best practices for branch naming and commit messages](https://dev.to/shnjd/git-good-best-practices-for-branch-naming-and-commit-messages-oj4)

### Categories

- `feature` – new features or functionality
- `fix` – bug fixes (reference issues when possible)
- `refactor` – code changes that are neither fixes nor features
- `documentation` – documentation updates
- `build/dependencies` – build system or dependency changes
- `test` – adding or updating tests
- `ci` – CI/CD changes (for example GitHub Actions)
- `translation` – translation updates
- `chore` – miscellaneous changes

### Additional guidelines

- Keep linting changes in separate commits
- Add comments where necessary
- Follow existing coding standards
- See [ESLint config](https://github.com/h5p/eslint-config-h5p)
- Ensure proposed changes are accessible ([WCAG 2.2](https://www.w3.org/WAI/WCAG22/quickref/?versions=2.2) AA compliant). The following [guidelines](https://www.w3.org/WAI/ARIA/apg/patterns/) may be helpful for ensuring screen reader compatibility. 

---

## 📐 Pull Request Guidelines

To help maintainers review your contribution efficiently:

- Ensure your commits follow the [commit conventions](#-commit-conventions)
- Keep PRs **small and focused**
- Clearly describe the problem and your solution
- Use a clear and descriptive PR title
- Reference related issues (for example `Fixes #123`)
- Follow existing code style and conventions
- Add or update tests and documentation when relevant
- Apply relevant labels (for example bug, feature, translation)

---

## 🐞 Reporting Issues

1. Navigate to the relevant repository
2. Check existing issues to avoid duplicates
3. Open a new issue using the appropriate template (Bug Report, Feature Request, and so on)

---

## Contributing Translations
### Content Types
For contributing translations for content types, you may edit the relevant language file for the respective repo under ./languages and make a pull request. For a complete overview of the Content Type translation status, you can check out [https://localization.h5p.org/](https://localization.h5p.org/).

### Drupal
Drupal translations are added through the [localize.drupal.org](https://localize.drupal.org/) community project.

### Moodle
Translations for Moodle plugin can be added or edited using [lang.moodle.org](lang.moodle.org). Read the [documentation](https://docs.moodle.org/502/en/Contributing_a_translation) to help you started. Select the component named 'hvp' (numbers aren't allowed in Moodle plugin name).

### Wordpress
If you wish to translate the UI texts of the plugin you can do it the following way for WordPress:

1. Go to the languages folder of the H5P plugin, copy the h5p-nb_NO.pot file and rename it to match your [ISO 639-1 language code](https://en.wikipedia.org/wiki/List_of_ISO_639_language_codes).
2. Open the file in your favorite text editor, or a program called [poedit](https://poedit.com/) (makes the job easier), and get on with your translating.
3. Upload the finished file to the [plugin's issue queue](https://github.com/h5p/h5p-wordpress-plugin/issues) or create a new forum post, and we'll add it to the next release of the plugin.


---

## 🧭 What to Expect

- 🤝 **Respectful communication**  
  We follow our [Code of Conduct](https://h5p.org/h5p-code-of-conduct)

- ⏳ **Review time**  
  Reviews may take time depending on the contribution.

  - Bug fixes, dependencies, and general enhancements → reviewed by community maintainers
  - Larger features and product-level changes → reviewed by the product team

- 🔄 **Feedback**  
  Reviewers may request changes — this is a normal part of collaboration.

- 🔒 **Merging**  
  Only maintainers can merge pull requests.

- 🚀 **Release workflow**  
  Approved contributions are prioritized for core team review and release.

  - Issue statuses: <https://github.com/orgs/h5p/projects/6>
  - Release overview: <https://help.h5p.com/hc/en-us>

---

## 🌍 Community Values

We believe in:

- 🤝 Open collaboration
- 📚 Knowledge sharing
- 🌈 Respect for diverse perspectives
- ✨ Transparency and kindness

---

## 📜 License

By contributing, you agree that your contributions will be licensed under the same license as the repository.
