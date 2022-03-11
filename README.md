# No Merge Commits

This GitHub action flags pull requests that contain merge commits.


## Usage

```
on: pull_request

name: Check Pull Request

jobs:
  pr-check:
    runs-on: ubuntu-20.04

    steps:
      - name: Check For Merge Commits
        uses: voxie-actions/no-merge-commits@v1
```

## License

This code is licensed under [The MIT License (MIT)](LICENSE), and was originally based on [Morishiri/block-merge-commits-action](https://github.com/Morishiri/block-merge-commits-action), which was in turn based on [xt0rted/block-autosquash-commits-action](https://github.com/xt0rted/block-autosquash-commits-action).
