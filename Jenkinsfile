pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Code checked out from GitHub'
            }
        }

        stage('Build') {
            steps {
                echo 'Building simple HTML project'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing HTML files'
                sh 'ls -l'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deployment stage will be added later'
            }
        }
    }
}