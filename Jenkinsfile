pipeline {
    agent {
        docker {
            image 'python:3.13.10-alpine3.23'
        }
    }
    stages {
        stage('Build') {
            steps {
                sh 'python --version'
                sh 'echo "Hello World"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}