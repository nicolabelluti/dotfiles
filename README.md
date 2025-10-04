<div align="center">

# ~/.dotfiles 🏡

[![chezmoi](https://img.shields.io/badge/chezmoi-4051b5)](https://chezmoi.io/)
[![Ansible](https://img.shields.io/badge/Ansible-ee0000?logo=ansible)](https://ansible.com/)
[![MIT License](https://img.shields.io/badge/License-MIT-dark_green)](https://choosealicense.com/licenses/mit/)

</div><br>

> My dotfiles, managed with [chezmoi](https://chezmoi.io/) and
> [Ansible](https://ansible.com/)

## Usage

Install [chezmoi](https://chezmoi.io/install/), then run:

```sh
# Initialize the repository
chezmoi init git.nicolabelluti.me/nicolabelluti
# You can also just use
# `chezmoi init nicolabelluti`
# if you want to use the GitHub mirror

# Apply the dotfiles
chezmoi apply
```

If you want to update the dotfiles:

```sh
chezmoi update --init
```

To give a new answer to the prompts:

```sh
chezmoi init --prompt
```
