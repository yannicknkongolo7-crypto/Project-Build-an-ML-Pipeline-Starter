# GitHub Release Notes & Next Steps

Tag `v1.0.0` has been created locally and pushed to `origin`.

Repository: https://github.com/yannicknkongolo7-crypto/Project-Build-an-ML-Pipeline-Starter

Since the GitHub CLI (`gh`) is not available in this environment, please use one of the options below to create the GitHub Release page:

Web UI (recommended):
1. Open the repository URL above in your browser.
2. Click on "Releases" > "Draft a new release".
3. Select the tag `v1.0.0` (it should be available), add a release title and the changelog from `RELEASES.md`, then publish.

Using GitHub CLI (if you have it locally):
1. Authenticate with `gh auth login`.
2. Run: `gh release create v1.0.0 --title "v1.0.0" --notes-file RELEASES.md` from the repo root.

If you want me to create the release page programmatically, install and authenticate `gh` locally and re-run these steps, or grant a token-based automation with guidance.
