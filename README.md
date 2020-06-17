<div style="text-align: center" align="center">

# Conways Game of CLIfe
[![License](https://img.shields.io/github/license/Sv443/Conways-CLIfe)](https://sv443.net/LICENSE)
[![Build Status](https://github.com/Sv443/Conways-CLIfe/workflows/build/badge.svg)](https://github.com/Sv443/Conways-CLIfe/actions)
[![Known Vulnerabilities](https://snyk.io/test/github/Sv443/Conways-CLIfe/badge.svg)](https://snyk.io/test/github/Sv443/Conways-CLIfe)
[![Discord](https://img.shields.io/discord/565933531214118942)](https://sv443.net/discord)  

![preview](./clife_preview.gif)

</div>

```
by Sv443
github.com/Sv443
contact@sv443.net
June 1, 2020
```

## Info:
Conway's Game of Life in the Command Line Interface.  
Features a bunch of premade presets, a random generator and an editor to create your own presets.  
I strongly recommend using CMD, Git Bash or zsh to run this since it renders better than other terminal apps.  

### This game is part of my [CLI Games Collection](https://github.com/Sv443/CLI-Games-Collection)
### You can download a standalone version here: [![(click)](https://img.shields.io/github/v/release/Sv443/Conways-CLIfe.svg)](https://github.com/Sv443/Conways-CLIfe/releases)

<br>

## Steps to build:

### Prerequisites
- Node.js  (I recommend the latest v14), node.js can be downloaded from [Nodes.js](https://nodejs.org/en/) and Npm [download](https://www.npmjs.com/get-npm)

### Download 
##### clone the repo and open a terminal in the downloaded folder
```bash
> git clone https://github.com/Sv443/Conways-CLIfe.git
```
### Install dependencies 
```bash
> cd /path/to/dowloaded/folder/Conways-CLIfe
> npm i
```

### to build the executables (which are located in the `dist` folder)
```bash
> npm run build
```
<br>

## Rules of Conway's game of life:
| &nbsp; | &nbsp; |
| --- | --- |
| Births | Each dead cell adjacent to exactly three live neighbors will become live in the next generation. |
| Death by isolation | Each live cell with one or fewer live neighbors will die in the next generation. |
| Death by overcrowding | Each live cell with four or more live neighbors will die in the next generation. |
| Survival | Each live cell with either two or three live neighbors will remain alive for the next generation. |

<br>

## Dependencies:
- [fs-extra](https://npmjs.com/package/fs-extra)
- [keypress](https://npmjs.com/package/keypress)
- [perlin-noise](https://npmjs.com/package/perlin-noise)
- [svjsl](https://npmjs.com/package/svjsl)
- [unzipper](https://npmjs.com/package/unzipper)

## links
- [Conway's game of life: wikipidea](https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life)
