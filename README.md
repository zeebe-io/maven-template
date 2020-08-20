# zeebe-maven-template
Empty maven project with defaults that integrate with the Zeebe build pipeline

## Usage
Use this as a template for new Zeebe projects.

Change the artifact, name and version in `pom.xml` and `.ci/scripts/github-release.sh`.

## Features
* GitHub Integration
  * Dependabot enabled for Maven dependencies (see `.github/dependabot`) 
* Maven POM
  * Zeebe reprositories
  * Release to Maven, Zeebe and GitHub
  * JUnit 4
  * AssertJ
  * Surefire Plugin
* Jenkinsfile
  * Rerun failed builds
  * Show last commit in build display name