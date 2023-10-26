<p align="center">
  <a href="https://cdsorg.vercel.app/">
    <img alt="CDS" title="CDS" src="https://github.com/CodeDeployingSquad/docs/blob/7fee7e648814aaafebf52852eb99b4e3654e8387/static/img/logo.png" width="200">
  </a>
</p> 
<h1 align="center">< CDS.Documentation /></h1>
<h4 align="center">Documentation for the largest community of tomorrow's open source developers 📚</h4>

<br>

<div align="center">
  <a href="https://github.com/CodeDeployingSquad?tab=repositories">
    <img src="https://img.shields.io/badge/Repositories-9-brightgreen.svg" alt="Repositories">
  </a>
  <a href="https://github.com/CodeDeployingSquad/graphs/contributors">
    <img src="https://img.shields.io/badge/Contributors-15-blue.svg" alt="Contributors">
  </a>
  <a href="https://github.com/CodeDeployingSquad/graphs/commit-activity">
    <img src="https://img.shields.io/badge/Commits-3200-orange.svg" alt="Commits">
  </a>
  <a href="https://github.com/CodeDeployingSquad/pulls">
    <img src="https://img.shields.io/badge/PRs%20Open-25-brightgreen.svg" alt="PRs Open">
  </a>
  <a href="https://github.com/CodeDeployingSquad/issues">
    <img src="https://img.shields.io/badge/Issues%20Open-50-red.svg" alt="Issues Open">
  </a>
  <a href="https://github.com/CodeDeployingSquad/network/members">
    <img src="https://img.shields.io/badge/Forks-30-lightgrey.svg" alt="Forks">
  </a>
  <a href="https://github.com/CodeDeployingSquad/stargazers">
    <img src="https://img.shields.io/badge/Stars-1500-yellow.svg" alt="Stars">
  </a>
</div>
<br>
<div align="center">
  <img alt="CDS" title="CDS" src="https://github.com/CodeDeployingSquad/docs/blob/2e9158698d3b06559f362f3a5ec05b3a9fd55c02/ss.png" width="100%" style="border-radius: 10px;">
</div>

<br>


## Table of Contents

- [Installation](#setup)
- [Local Development](#localdevelopment)
- [Build](#build)
- [Deployment](#deployment)
- [Continuous Integration](#ci)
- [Deployed on GitHub Pages](#ghpages)
- [Contributors](#contributors)

<br>

### Installation

```
$ pnpm install
```

### Local Development

```
$ pnpm run start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

### Build

```
$ pnpm run build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

### Deployment

Using SSH:

```
$ USE_SSH=true pnpm run deploy
```

Not using SSH:

```
$ GIT_USER=<Your GitHub username> pnpm run deploy
```

If you are using GitHub pages for hosting, this command is a convenient way to build the website and push to the `gh-pages` branch.


### Continuous Integration

Some common defaults for linting/formatting have been set for you. If you integrate your project with an open source Continuous Integration system (e.g. Travis CI, CircleCI), you may check for issues using the following command.

```
$ pnpm run ci
```

### Deployed on GitHub Pages

This project is deployed on GitHub Pages, a static site hosting service that lets you publish HTML, CSS, and JavaScript files to the web directly from a GitHub repository.

To view the live site, visit:

[https://codedeployingsquad.github.io/docs](https://codedeployingsquad.github.io/docs)

### Contributors

<a href="https://github.com/CodeDeployingSquad/docs/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=CodeDeployingSquad/docs" />
</a>
