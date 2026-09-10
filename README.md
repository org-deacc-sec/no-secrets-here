# no-secrets-here

Repository fixtures for testing what repository data can be restored after deletion.

## Restore test assets

This repository now includes:

- workflow definitions under `.github/workflows`
- a manual workflow that generates clear job logs and uploads an artifact bundle
- a second manual workflow that produces multiple job logs
- sample repository content under `restore-test-assets`

## Added workflows

- `restore-test-logs-and-artifacts.yml`: creates deterministic logs and uploads an artifact bundle
- `restore-test-matrix.yml`: creates multiple manual-run jobs with distinct logs

## Added repository content

- `restore-test-assets/README.md`
- `restore-test-assets/data/inventory.json`
- `restore-test-assets/data/checkpoints.csv`
- `restore-test-assets/notes/timeline.txt`
