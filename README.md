# pre-commit: editorconfig-checker mirror

Mirror of [editorconfig-checker](https://github.com/editorconfig-checker/editorconfig-checker) package for [pre-commit](https://pre-commit.com/).

## Usage

Add this to your `.pre-commit-config.yaml`:

```yaml
- repo: https://github.com/skycaptain/pre-commit-editorconfig-checker
  rev: ''  # Use the sha / tag you want to point at
  hooks:
    - id: editorconfig-checker
```
