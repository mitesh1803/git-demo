pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                echo 'Checked out repo successfully'
            }
        }
        stage('Build') {
            steps {
                sh 'python3 new.py'
            }
        }
    }
}
