Docker image for Azure Pipelines, created by following the [official documentation](https://docs.microsoft.com/en-us/azure/devops/pipelines/agents/docker?view=azure-devops#create-and-build-the-dockerfile-1)

## Build

`cd dockeragent`
`docker build -t vfabing/dockeragent .`

## Push manually to Docker Hub

`docker push vfabing/dockeragent`
