## Development/Contributing

### Getting Started

1. Clone this repository
2. Create a new branch to do your work
3. Run `npm i` in  the directory root
4. Follow commit convention below & push changes
5. Create and fill out a (*Pull Request*)

### Pushing Changes

1. Make your fixes, edits, changes, updates, etc. Commit your changes (using [conventional commits](https://www.conventionalcommits.org/en/v1.0.0-beta.4/) -- &see more info below*) and push to your branch.
2. When you're ready to merge, create a PR (pull request) to be reviewed

**Note:** If necessary, update any relevant documentation according to your changes. If your merge creates breaking changes, have a plan in place to ensure the necessary people are aware of your changes.

### Commits

Camp uses [standard-version](https://github.com/conventional-changelog/standard-version) to automatically update the changelog and do versioning. Please use [conventional commits](https://conventionalcommits.org/) for this.

**Commit format:**

```
// type: ['build', 'ci', 'chore', 'docs', 'feat', 'fix', 'perf', 'refactor', 'revert', 'style', 'test']
// scope (optional): ['camp-color', 'camp-css', etc. ]
// description: lowercase
// body (optional): More optional details
// footer (optional): More optional meta details

type(scope?): description
body?
footer?
```

**Example commit messages:**

- `git commit -m "feat: added a new package"`
- `git commit -m "docs: update docs"`
- `git commit -m "fix(camp-color): typo in token name"`
- `git commit -m "feat(camp-typography): changes product specific token"`
- `git commit -m "chore: upgrade devDependencies to latest version"`