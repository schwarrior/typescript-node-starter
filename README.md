typescript-node-start
=====================

▀▀█▀▀ ▒█▀▀▀█ 
░▒█░░ ░▀▀▀▄▄ 
░▒█░░ ▒█▄▄▄█ 

▒█▄░▒█ █▀▀█ █▀▀▄ █▀▀ 
▒█▒█▒█ █░░█ █░░█ █▀▀ 
▒█░░▀█ ▀▀▀▀ ▀▀▀░ ▀▀▀ 

▒█▀▀▀█ ▀▀█▀▀ █▀▀█ █▀▀█ ▀▀█▀▀ 
░▀▀▀▄▄ ░░█░░ █▄▄█ █▄▄▀ ░░█░░ 
▒█▄▄▄█ ░░▀░░ ▀░░▀ ▀░▀▀ ░░▀░░


# Introduction

This starter project demonstrates one working setup for a new Node.js program to be written in TypeScript. The relationships between NPM package config, TypeScript config, and Lint can be difficult to get right.

# Setup Actions

1) Install NPM packages and types. From console, at directory root of project: 'npm install'
2) Build or watch Typescript. From console: 'tsc watch' or 'tsc build'
3) Run built project. From console: 'node build/index.js'. Debug in VS Code: 'Run' Menu: 'Start Debugging'

You may see some errors like 'Node type not found' or 'Console not found' if you attempt to build or run before running 'npm install'.

# Code Style Rules

The code style rules (defined and managed by ESLINT which has replaced TSLINT) have been modified slightly for a few preferences. You can change these preferences inside the .eslintrc.json file.

- Do not require end of line semicolons
- Prefer single quotemarks
