# Orion Book

<a href="https://orion-book.netlify.app/"><img alt="Website" src="https://img.shields.io/netlify/f0f99d3f-95b1-4ce4-b7ae-6d6c8d52eea8?style=for-the-badge&logo=netlify"></a>
<a href="https://github.com/mwitomski-official/orion-jupyter-book/LICENSE.txt"><img alt="GitHub" src="https://img.shields.io/github/license/mwitomski-official/orion-jupyter-book?style=for-the-badge"></a>
<a href="https://github.com/mwitomski-official/orion-jupyter-book/commits"><img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/mwitomski-official/orion-jupyter-book?style=for-the-badge"></a>
<a href="https://orion-book.netlify.app/"><img alt="Website" src="https://img.shields.io/website?down_color=lightgrey&down_message=offline&style=for-the-badge&up_color=green&up_message=online&url=https%3A%2F%2Fmwitomski-official.github.io%2F"></a>

[![Netlify Status](https://api.netlify.com/api/v1/badges/f0f99d3f-95b1-4ce4-b7ae-6d6c8d52eea8/deploy-status)](https://app.netlify.com/sites/orion-book/deploys)

🌱 The Jupyter book with interesting examples (project Orion).

## Usage

### Building the book

If you'd like to develop and/or build the Orion Book book, you should:

1. Clone this repository
2. Run `pip install -r requirements.txt` (it is recommended you do this within a virtual environment)
3. (Optional) Edit the books source files located in the `orion-jupyter-book/` directory
4. Run `jupyter-book clean orion-jupyter-book/` to remove any existing builds
5. Run `jupyter-book build orion-jupyter-book/` or `jupyter-book build .`

A fully-rendered HTML version of the book will be built in `orion-jupyter-book/_build/html/`.

### Hosting the book

Please see the [Jupyter Book documentation](https://jupyterbook.org/publish/web.html) to discover options for deploying a book online using services such as GitHub, GitLab, or Netlify.

For GitHub and GitLab deployment specifically, the [cookiecutter-jupyter-book](https://github.com/executablebooks/cookiecutter-jupyter-book) includes templates for, and information about, optional continuous integration (CI) workflow files to help easily and automatically deploy books online with GitHub or GitLab. For example, if you chose `github` for the `include_ci` cookiecutter option, your book template was created with a GitHub actions workflow file that, once pushed to GitHub, automatically renders and pushes your book to the `gh-pages` branch of your repo and hosts it on GitHub Pages when a push or pull request is made to the main branch.

## Contributors

We welcome and recognize all contributions. You can see a list of current contributors in the [contributors tab](https://github.com/mwitomski-official/orion-jupyter-book/graphs/contributors).

## Credits

This project is created using the excellent open source [Jupyter Book project](https://jupyterbook.org/) and the [executablebooks/cookiecutter-jupyter-book template](https://github.com/executablebooks/cookiecutter-jupyter-book).
