# Jenkins Sample Build Repository

A small Java Maven project designed for practicing Jenkins CI.

## What Jenkins will do

1. Clone this repository
2. Compile the application
3. Run unit tests
4. Package the application as a JAR
5. Archive the JAR as a Jenkins build artifact

## Jenkins setup

Create a Pipeline job and use **Pipeline script from SCM**.

SCM: Git
Repository URL: your GitHub repository URL
Script Path: Jenkinsfile

Example GitHub repository:
`https://github.com/YOUR-USERNAME/jenkins-sample-repo.git`

## Local build

```bash
mvn clean test package
```

The JAR will be created under `target/`.
