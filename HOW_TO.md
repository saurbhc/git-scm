# Guide: For 1st time Contributions to Open Source

1. Make sure you have `gh` installed
2. Login with `gh`
  ```bash
  gh auth login --web
  ```
3. Fork & Clone the repo  (with `gh`)
  ```bash
  gh repo fork https://github.com/<org>/<repo>/pull/<\#> --clone
  ```
4. Create branch <feat/feature>
  ```bash
  git checkout -b feat/feature
  ```
5. Modify files, commit, and push
  ```bash
  git commit -m "add feature"
  git push origin HEAD
  ```
6. Go to `https://github.com/<org>/<repo>/pull/<#>` and create Pull Request
  with base branch as their master/main branch
