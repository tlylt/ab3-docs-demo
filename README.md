# AddressBook Level 3 Documentation with MarkBind
Demo the deployed MarkBind site for AddressBook Level 3 documentation.

- [Docs with MarkBind](https://tlylt.github.io/ab3-docs-demo/)
- [_Orignal_ Docs with Jekyll](https://se-edu.github.io/addressbook-level3/)

## Common issues

- Action failed with `Error: Action failed with "The process '/usr/bin/git' failed with exit code 128"`
  - Go to GitHub Repo Settings > Actions > General > Workflow permissions > Select `Read and write permissions`
- Page not found
  - Wait for a few minutes for GitHub Pages to build the site
  - Go to GitHub Repo Settings > Pages
    - Source should be "Deploy from a branch"
    - Branch should be "gh-pages", "/(root)"
