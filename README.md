# Introduction
This repository is a [https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template](template repository)

When you want to create a new TRE repository, you should do so by using this template.  Hint: click the green button above that says "Use this template"

# Why
We want to ensure that all repositories in TRE follow defined conventions and standards. See [The TRE Engineering Handbook](https://github.com/nationalarchives/da-tre-engineering-handbook)

Specifically this repository mandates a minimal set of [pre-commit hooks](https://pre-commit.com/)

It is therefor required that you use pre-commit and the [https://github.com/Yelp/detect-secrets](detect secrets) tool/hook.

They can generally be installed with pip. e.g.

```
pip install pre-commit
pip install detect-secrets
```

# Contents
```README.md```

```.pre-commit-config.yaml``` - Sensible default to get you started.  Add the hooks you need accordingly.

``` .secrets.baseline``` - A baseline file for detect-secrets that assumes there should be no secrets in this repository.
