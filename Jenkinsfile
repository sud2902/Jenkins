pipeline {
    agent any
    tools {
        MavenDefault 'apache-maven-3.6.3' 
    }
    stages {
        stage('Build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}
