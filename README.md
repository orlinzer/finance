# Finance Repositories

## Description

This repository contains a collection of finance-related repositories that I have created. Each repository contains a README file that describes the repository in more detail.

## Project Management

- [**`Finance`**](https://github.com/users/orlinzer/projects/4)

## Repositories

- [**`finance-documentation`**](https://github.com/orlinzer/finance-documentation)
- [**`finance-binance-getaway`**](https://github.com/orlinzer/finance-binance-getaway)
- [**`finance-predictions-service`**](https://github.com/orlinzer/finance-predictions-service)
- [**`finance-repositories`**](https://github.com/orlinzer/finance-repositories)
- [**`finance-ui-components`**](https://github.com/orlinzer/finance-ui-components)
- [**`finance-web-ui`**](https://github.com/orlinzer/finance-web-ui)

## Usage

First use the following commands to clone the repository and its submodules.

```bash
git clone git@github.com:orlinzer/finance-repositories.git
cd finance-repositories
git submodule update --init --recursive
```

To update the repository and its submodules, run the following commands.

```bash
git fetch
git pull
git submodule update --init --recursive
```

To add a submodule, run the following commands.

```bash
git submodule add <repository-url> <repository-name>
```

To remove a submodule, run the following commands.

```bash
git submodule deinit -f <repository-name>
git rm -f <repository-name>
rm -rf .git/modules/<repository-name>
```
