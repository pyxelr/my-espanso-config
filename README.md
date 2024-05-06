# My espanso config

The configuration I am using in [espanso](https://espanso.org/) (open-source text-expander) to quickly type/run different commands on macOS.

## Usage

1. Install [espanso](https://espanso.org/install/).
2. Place the contents of `config/` and `match/` folders within your espanso config directory, which can be found with `espanso path` (typically: `$HOME/Library/Application Support/espanso`).
3. Start using espanso, e.g. by
   1. pressing `CMD+SHIFT+SPACE` to display espanso search bar (list of all available commands in the current context).
   2. typing `;esp` and pressing space to expand into `"code ~/Library/Application\\ Support/espanso/"` (for viewing/editing your espanso config in VS Code).

See [espanso.org/docs/](https://espanso.org/docs/) for the official documentation.

## Match files

Generally, all the `*.yml` files attempt to be self-explanatory with a couple of file comments. I decided to expand everything after pressing space; however, you may also consider using [word triggers](https://espanso.org/docs/matches/basics/#word-triggers).

List of `match/` files:

- `_obsidian.yml` - [Obsidian](https://obsidian.md/) snippets, e.g. for font coloring
- `_terminal.yml` - snippets that function only within [iTerm](https://iterm2.com/), default macOS Terminal or [VS Code](https://code.visualstudio.com/), e.g. for editing/syncing espanso config, or for file/folder search
- `base.yml` - default match file
- `conda.yml` - [Conda](https://github.com/conda/conda) snippets
- `docker.yml` - [Docker](https://www.docker.com/) snippets
- `git.yml` - [Git](https://git-scm.com/) snippets
- `kubernetes.yml` - [Kubernetes](https://kubernetes.io/)/[kubectl](https://kubernetes.io/docs/reference/kubectl/) snippets
- `languages.yml` - language accents (currently French and German)
- `markdown.yml` - Markdown snippets
- `personal.yml` - personal snippets
- `python.yml` - Python snippets
- `symbols.yml` - special characters, e.g. dash, ellipsis, bullet point, left arrow, ...

> [!NOTE]  
> _Some files may require custom edit (marked with `...`)._
