---
sort: 1
---

## Continous Integration

Continuous Integration is the process where developers integrate code into Bitbucket frequently, preferably several times a day. Each integration  So in our project, whenever a developer commits his/her changes in the Bitbucket. Respective commit will initiate a build in Jenkins and based on the type of committed branch, Jenkins initiates respective job in Multi-Branch Pipeline.  That is, If the commit is from a feature branch, Jenkins will execute its respective Feature Branch Job.

{% include list.liquid all=false %}