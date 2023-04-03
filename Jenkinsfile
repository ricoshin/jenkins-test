/* Requires the Docker Pipeline plugin */
pipeline {
    agent { docker { image 'python:3.10.7-alpine' } }
    stages {
        stage('Sanity Check') {
            steps {
                input "Go for it?"
            }
        }
        stage('Deploy') {
            steps {
                sh "echo 'Deploy!'"
            }
        }
    }
}