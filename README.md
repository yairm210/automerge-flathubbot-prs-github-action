# Flatpak External Data Checker replacement for deprecated automerge-flathubbot-prs

On June 17th 2024 Flathub [disabled the "automerge-flathubbot-prs" setting in flathub.json](https://docs.flathub.org/blog/linter-restricting-automatic-merge/) due to misuse.

Some of us, however, have *many* distribution venues and many releases, and we *need* this automation in order for Flathub to be a viable distribution platform.

[This Github Action 'pipeline'](/.github/workflows/automerge-flathubbot-updates.yml) is a way to get your automation back. Rather than wrapping it as a "proper" Github Action, I feel it is better to provide the script "as is" - since it's a single step - to allow for changes relevant to your specific package.
