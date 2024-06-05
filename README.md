# Shared GitHub Actions

## Description

This repository contains a set of common, reusable GitHub Actions that assist in creating pipelines.

## Table of Contents

<!-- NOTE: To update doctoc please run `npx doctoc ./README.md --notitle` -->

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

- [Installation](#installation)
- [Semantic Versioning and NPM](#semantic-versioning-and-npm)
- [License](#license)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Installation

To use these actions in your GitHub workflows, you can refer to them using the `uses` keyword in your workflow file. For example:

```yaml
steps:
    - name: Use Shared Action
        uses: silte/actions/shared-github-actions@v1
```

## Semantic Versioning and NPM

This project uses semantic versioning. You can update the version of your project using the npm version command followed by major, minor, or patch. For example:

```bash
npm version patch
```

This will update the patch version of your project. Similarly, you can update the major or minor versions:

```bash
npm version minor
npm version major
```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
