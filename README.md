<h1 align="center">
	<img src="docs/images/banner.png" alt="stalkr | GitHub | Commits Feed">
	<br>
	<br>
</h1>

<br>
<br>

<p align="center">
	<a href="https://getstal.kr">stalkr</a> micro service which feeds our clients with GitHub push events.
</p>

<br>

---

<p align="center">
	<a href="">
	<img
	src="https://img.shields.io/badge/stalkr-example-orange.svg" alt="Sample Badge">
	</a>&nbsp;&nbsp;&nbsp;
	<a href="">
	<img
	src="https://img.shields.io/badge/stalkr-example-orange.svg" alt="Sample Badge">
	</a>
</p>

<br>

## Table of Contents

<!-- DO NOT EDIT THE COMMENTS BELOW -->

<!-- toc -->

<!-- tocstop -->

## What

### Our Product

<p align="center">
	<img src="docs/images/logo.png" alt="stalkr Logo" width="400px">
</p>

*stalkr* is a simple–yet powerful–set of tools which gathers data from both continuous integration and application infrastructure monitoring tools in order to make it easier to monitor the whole developing process, in a way the entire team can see at a glance, from the very first commit to the final release.

Although our experimental release is a simple client made for the  TV, we do intend to make *stalkr* clients available on as much platforms as possible, which include:

- Other **Smart TV** platforms–e.g. Android TV, webOS, Tizen etc.;

- **SmartWatch** platforms–e.g. watchOS, Android Wear etc.;

- Popular **Mobile** platforms–e.g. iOS, Android etc.;

- Popular **Desktop** OSs–e.g. macOS, Linux, Windows etc.;

- The **Web** itself.

If you can't wait to check it out:

<p align="center">
  <a href="https://itunes.apple.com/br/app/.../...">
    <img alt="Download on the App Store" src="docs/images/badge.png" width="150px">
  </a>
</p>

### How it Works

#### Architectural Overview

> easy peasy lemon squeezy!

<p align="center">
  <a href="https://itunes.apple.com/br/app/.../...">
    <img alt="Download on the App Store" src="docs/images/stack-overview.png" width="900px">
  </a>
</p>

##### The Registry

> Coming soon.

Use the *stalkr* **Package Catalog**/Registry to quickly and easily find open-source packages to speed your development.

It basically discovers all the available *stalkr* plugins in popular back-end registries out there–e.g. *[node.js](https://nodejs.org/en/)-based* plugins available [npmjs.com](https://www.npmjs.com/) registry can be discovered if they contain `stalkr-plugin` value in `keywords` field of `package.json`.

##### The CLI

> Coming soon.

Use the *stalkr* **CLI** to quickly bootstrap and deploy your packages right from your terminal.

It basically works as an abstraction layer over commom CLI tools used to get a *stalkr* package up and running.

##### Clients

As stated above, we do intend to have multiple clients to fetch data from your deployed micro services.

###### Smart TVs

<p align="center">
	<img src="docs/images/screenshot_main.png" alt="stalkr  TV" width="650px">
</p>

Right now, only the  TV one is available for download at the [App Store]().

##### The Cloud

> Coming soon.

The *stalkr* **Cloud** is *PaaS* which behaves as one our revenue streams and helps your organizing your projects across **organizations**, **teams**, **roles** etc.

**Organizations** are great for creating distinct groups of users within your company, such as divisions or groups working on similar projects.

**Teams** give organizations the ability to create groups of members and control access to projects. Team members can be granted read, write, or admin permissions to specific projects.

## Usage

### Getting Started

1. Make sure you define the `ENV` variables below:

    ```sh
    # Pusher credentials
    export PUSHER_ID='300844'
    export PUSHER_KEY='5cdc3c711f606f43aada'
    export PUSHER_SECRET='7bf9214d039b830b3b3c'

    # GitHub credentials
    export GITHUB_TOKEN='f039816270db489b0a062b659ff51be6a73cee69'

    # Basic stalkr cell metadata
    export STALKR_TEAM='myTeam'
    export STALKR_PROJECT='myProject'
    ```

1. Clone this repository:

    ```sh
    git clone https://github.com/stalkr-io/github-commits-feed
    ```

1. Install all dependencies:

    ```sh
    # via npm
    npm install
    # or using yarn
    yarn
    ```

1. Launch it:

    ```sh
    # via npm
    npm start
    # or using yarn
    yarn start
    ```

If everything goes okay, it should now be running at [`localhost:3000`](http://localhost:3000).