# Silesian Solutions organization defaults

This public repository contains default community health files for repositories in the **silesiansolutions** GitHub organization.

Repositories that do not define their own version inherit:

- **.github/PULL_REQUEST_TEMPLATE.md**
- **CONTRIBUTING.md**
- **SECURITY.md**

A repository-specific file takes precedence over the organization default. Defaults become active after they are merged into this repository's default branch.

The workflow and Semgrep rule in this repository maintain and demonstrate the shared GitHub Actions security policy; workflows are not inherited automatically by other repositories.

GitHub does not inherit **CODEOWNERS** from this repository. The **.github/CODEOWNERS** file must also be synchronized to every repository, and the referenced team must have explicit write access there.
