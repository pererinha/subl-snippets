subl-snippets
=============

Some snippets I use during my day.

### Installation

For installation, run the following script in the Sublime Text terminal (ctrl+`) which utilizes git clone.

```python
import os; path=sublime.packages_path(); (os.makedirs(path) if not os.path.exists(path) else None); window.run_command('exec', {'cmd': ['git', 'clone', 'https://github.com/pererinha/subl-snippets', 'snippets'], 'working_dir': path})
```
