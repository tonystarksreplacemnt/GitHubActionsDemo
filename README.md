## GitHubActionsDemo
#### Topics
1. What is GitHub Actions
2. How to use - Step by Step DEMO
3. A demo workflow file - how to create, run and check results
4. Terms: Workflows, Events, Jobs, Steps

#### Features in Github to create custom Automated Workflows
- Automate SDLC workflows
- Implement CI CD DevOps

#### DEMO
```
Step 1 - Signup and Login to Github.com
Step 2 - Create a new Repository
Step 3 - In the repo, create a folder .github/workflows
Step 4 - In the folder, create a YAML file with .yml extension
Step 5 - Add the content of the workflow in the file
Step 6 - Commit and push the changes
Step 7 - Goto Repo main page and click "Actions" tab
Step 8 - Select the workflow from left sidebar and check the logs and results
```

#### Terms
  ```
  WORKFLOW: a collection of jobs defined in a YAML file
  name:

  EVENTS: any activity in the repo that can trigger a workflow
  on:

  JOBS: a collection of steps
  jobs:

  STEPS: actions to be taken, commands, scripts
  steps:

  Chain Jobs-:needs
 ```

#### Reference
- https://gist.github.com/weibeld/f136048d0a82aacc063f42e684e3c494

#### Google yaml formatter sites
- https://jsonformatter.org/yaml-formatter
- https://codebeautify.org/yaml-beautifier

#### Pipeline Stages Example
```
Coding Stage
Building Stage
Deploying QA Env Stage
Testing Stage
Release Stage
```
### CI Tools- Githubs Replacemnt for Jenkins
* Github Actions
