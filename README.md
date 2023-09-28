# Random Azure DevOps stuff

Random snips of Azure DevOps pipeline to perform little tasks and actions.

### pipeline-rename-files.yaml

Pipeline to find files and add a prefix to the filename of each matching file.

### pipeline-publish-secure-files.yaml

Pipeline to publish AOD Secure Files as pipeline artifacts so they can be edited and re-uploaded.

Needs to be locked down/secured with ADO permissions etc.

### pipeline-jest-shard.yaml

Pipeline to shard JestJS tests (calls steps/jest_tests.yaml).
