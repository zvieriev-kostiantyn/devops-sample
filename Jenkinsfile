pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hi, it\'s build step"'
            }
        }
        stage('Test') {
            steps {
               sh 'echo "Hi, it\'s test step"'
            }
        }
        stage('Deliver') {
            steps {
                sh 'echo "Hi, it\'s deliver step"'
            }
        }
    }
}