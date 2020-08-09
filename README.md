# Install Atlassian SDK GitHub Action

[![Build status](https://github.com/rodrigo-nogues/github-action-install-atlassian-sdk/workflows/CI/badge.svg)](https://github.com/rodrigo-nogues/github-action-install-atlassian-sdk/actions?query=workflow%3A%22CI)

This action install the latest Atlassian SDK and runs `atlas-version` to validate the installation. Useful to build your Atlassian plugins.
At the moment it only works on Linux runners (tested ubuntu-latest).

## Usage

```yaml
uses: rodrigo-nogues/github-action-install-atlassian-sdk@v1
```
