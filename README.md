# Modern Frontend Web App

Configure and install a modern frontend application.

## Nodejs and npm

Follow the steps below to ensure you are on the latest version of node and npm.

### Install Nodejs

Download and install Nodejs: [Nodejs website](https://nodejs.org/en).

### Update Nodejs

Install n to manage node versions. It needs to be installed globally.

```bash
npm install -g n
```

Install the LTS version of node.

```bash
n lts
```

Remove previously installed versions.

```bash
n prune
```

### Update NPM

Ensure NPM is on the latest version available for you current Nodejs installation.

```bash
npm install -g npm@latest
```

## Yarn

### Enable Corepack

Corepack is included by default with all Node.js installs, but is currently opt-in. To enable it, run the following command.

```bash
corepack enable
```

### Updating the global Yarn version

Ensure yarn on the latesd stable version.

```bash
corepack prepare yarn@stable --activate
```

### Initializing your project

Just run the following command. It will generate some files inside your current directory; add them all to your next commit, and you'll be done!

```bash
yarn init -2
```

## Webpack

### Install webpack

Add webpack on your project.

```bash
yarn add webpack --dev
```
