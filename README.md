#Multi Branch Pipeline (Gitflow)

This project aims to create a pipeline which supports the [Gitflow Workflow](https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow) design.  
We want our pipeline to support _production_, _development_, _release_, _feature_ and _hotfix_ branches.

When using the gitflow cli the branch naming is:  
- Feature branches [feature/***]
- Release branches [release/***]
- Hotfix branches [hotfix/***]

When a new branch is created an pushed to github it will trigger a CI job for the new branch.  

## Assumptions  
* gitflow is installed on your workstation 

```bash
brew install git-flow
```
 ## Required Jenkins Plugins  
* multibranch pipeline plugin
* github plugin


