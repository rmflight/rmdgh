# 0.3.0

- Depend on `{rmarkdown}` >= 2.15, thanks @rmflight
- Breaking change: `github_issue()` wrap argument now defaults to `"auto"`, was `"preserve"`.
- Breaking change: `draft_issue` now accepts a `path` argument that has a configurable default in option `rmd_gh_issue_draft_path`. This replaces the `tempdir` argument.
- Generated issue thread Rmd document names now preserve case.
- Added `save_issue()` to save issues in a configurable folder which is automatically created and added to `.Rbuildignore` if it does not exist. The default is `./issues`. Thanks @Robinlovelace