### Step to step to create extension

```bash
$ cookiecutter https://github.com/jupyterlab/extension-cookiecutter-ts

# Install dependencies
$ yarn install

# Build Typescript source
$ jlpm build

# Link your development version of the extension with JupyterLab
$ jupyter labextension link .

# Rebuild Typescript source after making changes
$ jlpm build

# Rebuild JupyterLab after making any changes
$ jupyter lab build

# Run localhost
$ jupyter lab -> run localhost


# check extension linked
$ cd /usr/local/share/jupyter/lab/extensions to check

```
