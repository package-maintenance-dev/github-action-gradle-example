[![find_unmaintained_packages](https://github.com/package-maintenance-dev/github-action-gradle-example/actions/workflows/workflow.yml/badge.svg)](https://github.com/package-maintenance-dev/github-action-gradle-example/actions/workflows/workflow.yml)

## [package-maintenance.dev](https://package-maintenance.dev)'s Github action usage example.

#### Introduction
This repository is an example of [Package maintenance GitHub action](https://github.com/package-maintenance-dev/github-action).
It includes nothing, but Gradle's `build.gradle` file with some more or less typical dependencies, including both well 
maintained and not very well one or even unsupported for the sake of demonstration purposes. 

Dependency Graph was enabled for this project, so this data has been populated by GitHub.
Find more information about it in `Related documentation` section.

Please note: Gradle is not supported out of the box by Github.
For SBOM submission [Gradle Dependency Submission](https://github.com/marketplace/actions/gradle-dependency-submission) action is used.

#### How to enable for your project
If you have a Gradle-based project hosted on GitHub, to use this action you need just:

- Enable 'Dependency Graph' for the repository;
- Set up an action (please, find example [here](https://github.com/package-maintenance-dev/github-action-maven-example/blob/main/.github/workflows/main.yml));
- Find dependencies' report in a run output along with a run result (please, find example [here](TODO));

#### Related documentation
- [GitHub Dependency Graph: How to enable Dependency Graph](https://docs.github.com/en/code-security/supply-chain-security/understanding-your-software-supply-chain/configuring-the-dependency-graph)
- [GitHub Dependency Graph: Supported ecosystems](https://docs.github.com/en/code-security/supply-chain-security/understanding-your-software-supply-chain/dependency-graph-supported-package-ecosystems)
- [Gradle Dependency Submission GitHub Action](https://github.com/marketplace/actions/gradle-dependency-submission)
