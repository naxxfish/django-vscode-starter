# Django Project Starter

This template provides the configuration for a [VS Code Remote Container](https://code.visualstudio.com/docs/remote/containers) with all of the pre-requisite configuration for a Django project.

We're using the Microsoft provided [Python 3 development container](https://github.com/microsoft/vscode-dev-containers/blob/main/containers/python-3/README.md) - using Python 3.10-bullseye (for arm64 compatibility with your shiny new M1/M2 Macbook). 

The remote container image also include NodeJS so that you could add a React frontend or similar should you wish. 

## Getting started

In VS Code, Ctrl-Shift-P then select `Remote-Containers: Open Folder in Container ...`

Once the container is built, create the Django app:

```
django-admin startproject myprojectname .
```

At this point you should be able to run the default Django app and start developing

## Running and Debugging

You can hit F5 to run the Django development server without debugging. This supports auto-reload whilst you work. 

You can also go to the Debugging tab in VS Code and launch the Django development server with debugging if you wish.


## Included Tools

* [black](https://github.com/psf/black)
* [pylint](https://pypi.org/project/pylint/)
* [pipenv](https://pipenv.pypa.io/en/latest/)

Format on save is enabled.

## Configuration

Everything should Just Work™️ out of the box - but you may have to reopen the terminal to activate the pipenv 
