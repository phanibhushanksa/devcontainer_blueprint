## Devcontainer broilerplate
* This repository has broilerplate code to setup an isolated development enviroment using Devcontainer. 

### Advantages of devcontainer
* Devcontainer helps the whole team to work in a consistent coding environment. 
* Using Devcontainer provides several advantages like, 
    * Consistent and reproducable development enviroment
    * Simplified setup
    * Isolated environment
* To learn more about Devcontainers, please refer to: [Devcontainers](https://code.visualstudio.com/docs/devcontainers/tutorial)

### Using the repo
* After cloning this repo, open the folder in Visual Studio code. 
* Go to command palette (Cmd+shift+p in Macbook), search for **reopen in container** and select that option.
* This will create a devcontainer based on the Dockerfile and devcontainer.json in the .devcontainer folder.
* Once the devcontainer is created, you can add your own files as per the project requirements. 
* [Poetry](https://python-poetry.org/docs/basic-usage/) is used as package manager. To add any new package use the command
```bash
poetry add <package-name>
```
* To remove any package, use the command:
```bash
poetry remove <package-name>
```