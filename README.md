The goal of this repository is to help building a workspace containing all spirit.io projects.
It also includes a set of vscode launchers and tasks.

# Build the workspace

## Requirements

* git
* npm v3

## Install globally required tools

```sh
npm install -g git-workspace npm-workspace
```

## Initialize the spirit.io-workspace repository

### Clone the workspace

```sh
git clone https://github.com/spirit-io/spirit.io-workspace.git
```

### To contribute on the spirit.io framework

```sh
git-workspace clone framework
```

This will clone the repository [spirit.io](https://github.com/spirit-io/spirit.io.git)

### To contribute on the connectors

```sh
git-workspace clone connectors
```

This will clone the repositories [spirit.io-mongodb-connectors](https://github.com/spirit-io/spirit.io-mongodb-connectors.git) 
and [spirit.io-redis-connectors](https://github.com/spirit-io/spirit.io-redis-connectors.git)

### To contribute on the applications

```sh
git-workspace clone applications
```

This will clone the repositories [spirit.io-admin-applications](https://github.com/spirit-io/spirit.io-admin-applications.git) 
and [spirit.io-sample-applications](https://github.com/spirit-io/spirit.io-sample-applications.git)

### To contribute on the documentation

```sh
git-workspace clone doc
```

This will clone the repositories [spirit-io.github.io](https://github.com/spirit-io/spirit-io.github.io.git) 


## Install all repositories dependencies and compile typescript sources

```sh
npm-workspace install
```

WARNING: On windows environment, you have to run this command with administrator's privileges.
