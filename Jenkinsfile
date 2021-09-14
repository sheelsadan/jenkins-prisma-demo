pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                echo ${HOME}
                sh 'docker build --no-cache -t test/test-image:0.1 .'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
