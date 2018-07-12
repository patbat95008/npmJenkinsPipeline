# Jenkins CI Examples
Example Jenkins pipeline scripts that show how to publish and 
promote an NPM binary.

# Requirements
The Jenkinsfile-build-publish script requires the 'npm' CLI is installed and available for the Jenkins CI user. To use the JFrog CLI to publish the build to a JFrog Artifactory installation, you will need to [download and install](https://jfrog.com/getcli/) the CLI and have an [Artifactory NPM repository](https://www.jfrog.com/confluence/display/RTF/Npm+Registry) called 'npm-snapshots' configured.

The Jenkinsfile-Promote script requires the JFrog CLI and two NPM repositories named 'npm-snapshots' and 'npm-releases'.
