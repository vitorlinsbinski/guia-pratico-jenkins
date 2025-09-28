pipeline {
    agent any

    stages {
        stage('Build docker image') {
            steps {
                sh 'echo "Executand o comando Docker Build"'
            }
        }

        stage('Push docker image') {
            steps {
                sh 'echo "Executand o comando Docker push"'
            }
        }

        stage('Deploy no Kubernetes') {
            steps {
                sh 'echo "Executand o comando kubectl apply"'
            }
        }
    }
}