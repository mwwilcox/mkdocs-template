# Simple Blog Documentation

This is a template for a simple blog documentation site using python and mkdocs.

## Initialize

To initialize the site simple clone the repo, install the python virtual environment and start the local development server.

If you want to deploy your doc site to github or other you can find some information in the [MkDocs Documentation](https://www.mkdocs.org/user-guide/deploying-your-docs/)

```bash
git clone https://github.com/mwwilcox/mkdocs-template.git
pipenv install
export LC_ALL=en_US.UTF-8
export LANG=en_US.UTF-8
pipenv run mkdocs serve -a localhost:8000
```

I have recently added a devcontainer to the repo.

I have included a bash helper script named `serve.sh` which will start the dev server

Direct your browser to <http://localhost:8000>

Happy blogging!
