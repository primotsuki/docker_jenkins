pipeline {
    agent any
    stages {
        stage('build docker image'){
            steps {
                sh 'docker-compose build'
            }
        }
        stage('run docker image') {
            steps {
                sh 'docker-compose up -d'
            }
        }
    }
}
