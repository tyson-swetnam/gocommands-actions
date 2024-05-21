# gocommands-actions

[![CyVerse Datastore](https://github.com/tyson-swetnam/gocommands-actions/actions/workflows/cyverse-datastore.yml/badge.svg)](https://github.com/tyson-swetnam/gocommands-actions/actions/workflows/cyverse-datastore.yml)

Use [GoCommands](https://learning.cyverse.org/ds/gocommands/) to push folders or data to CyVerse from GitHub using an Action.

View our Action in [.github/workflows/](.github/workflows)

## GitHub Actions Workflow

This project uses a GitHub Actions workflow defined in [.github/workflows/cyverse-datastore.yml](.github/workflows/cyverse-datastore.yml). 

The workflow is named "CyVerse Datastore" and it is triggered on every push or pull request to the `main` branch. 

It performs the following steps:

1. Checks out the repository.
2. Sets up Python with version 3.x.
3. Downloads and installs latest version of GoCommands.
4. Sets up CyVerse Credentials.

For more details, please refer to the [workflow file](.github/workflows/cyverse-datastore.yml).
