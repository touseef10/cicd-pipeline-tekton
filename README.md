In this task I have created a Tekton Pipeline with three stages, i.e. Compile, Build, and Deploy.

In the first stage Compile I have git cloned the Git Repo and then Maven cleaned it.

In the second stage Build I have docker build and pushed Docker Image to my Docker Registry.

In the third stage Deploy I have deployed the my service on the local Kubernetes cluster.

