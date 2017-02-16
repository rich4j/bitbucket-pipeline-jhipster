# bitbucket-pipeline-jhipster
## Bitbucket JHipster pipeline Docker image with support for yarn

Inspired by laszlomiklosik/jhipster-bitbucket-pipeline

Example usage in bitbucket-pipelines.yml file:

```
image: richardfanning/bitbucket-pipeline-jhipster

pipelines:
  default:
    - step:
        script:
          - ./gradlew clean bootRepackage
```

Docker image info: https://hub.docker.com/r/richardfanning/bitbucket-pipeline-jhipster/