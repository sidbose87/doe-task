# DOE-DevOps-Task

This Repo lets you create a jenkins job which will create cross-platform script to provide it's hostname and date.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

## Prerequisites

You need to copy the contents of .ssh folder of pre-req in order for your local jenkins master to have access to repo with the provided ssh keys. 

## Assumptions

Jenkins is installed with sudo access to run some system related commands for linux

## Instructions

Copy contents of jenkins/jobs folder to your local jenkins master.

Or use
1. Configurator.bat (For windows to set up your environment by moving files from this repo)
2. Configurator.sh (For linux to set up your environment by moving files from this repo)

## Examples

Just open jenkins console and run the build job for Linux doe-pr01, similarly for windows

## Deployment

Trigger doe-pr01 which will in turn trigger consecutive job.

## Authors

    Sid

## License

This project is licensed under the MIT License - see the LICENSE.md file for details
