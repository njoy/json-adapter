# json-adapter
A repository which adapts the [Json](https://github.com/nlohmann/json) project for use in the NJOY21 build scheme.

## Git Subtree
This repository uses a git subtree for the directory `src`. The remote from which the subtree is made is located at [https://github.com/nlohmann/json](https://github.com/nlohmann/json). Equivalently, you can use the ssh location at `git@github.com:nlohmann/json.git`.

To facilitate updating the subtree when it gets updated upstream, do the following:

```bash
# This only needs to be done once
git remote add json https://github.com/nlohmann/json.git

# Do this when you need to update the subtree
git subtree pull --prefix=src json master
```

# License
The code contained in this directory is covered by the license contained in the [LICENSE](LICENSE) file. The code in the `src` directory is covered by it's own [LICENSE](src/LICENSE.MIT).

