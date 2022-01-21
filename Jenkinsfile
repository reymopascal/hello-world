// Hello-world build pipeline
pipeline {
    agent any

    tools {
        maven "Maven 3.6.3"
    }
    stages {
        stage('Build Hello-world-Maven') {
           steps{
              // Run the maven build
              sh "mvn clean install package"
           }
        }
    }
}