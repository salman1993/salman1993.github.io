---
layout: post
title:  "Open branch repo in GitHub UI"
date:   2023-04-05
categories: git github
---
A command I have been using a ton lately is:
```bash
gh browse --branch $(git rev-parse --abbrev-ref HEAD)
```
It requires the `git` & the GitHub CLI to be installed. If your current working directory is 
a GitHub repo, this command opens up the GitHub UI.
