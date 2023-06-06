/* Requires the Docker Pipeline plugin */
pipeline {
    agent { docker { image 'gradle:jdk11-jammy' } }
    stages {
        stage('build') {
            steps {
                sh 'gradle --version'
            }
        }
    }
}
