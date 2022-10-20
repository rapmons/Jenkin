pipeline {
  agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sh 'pip install -r requirements.txt'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
                sh 'python demo.py'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}