# exp cli tools test app

A repo to demo either a bug in exp cli tools or a misunderstanding on my part, when useing the "nodeModulesPath" setting.

## Installation

- clone the repo
- yarn install

## Getting Started

- change the absolute path in package.json, in the start script, to the absolute path location of the testapp folder
- change the absolute path in testapp/exp.json to the absolute path location of the node_modules folder in this folder
- yarn start

## Results

The command seems to get stuck waiting for the package manager to start up.