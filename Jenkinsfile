pipeline {
    agent { docker { image 'maven:3-jdk-13' } }
    stages {
        stage('build') {
            steps {
                sh ```
                  javac --version
                  mvn --version
                ```
            }
        }
    }
}