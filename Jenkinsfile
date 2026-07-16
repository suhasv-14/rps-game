pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('List Files') {
            steps {
                bat 'dir'
            }
        }

        stage('Build') {
            steps {
                echo 'HTML project does not require compilation.'
            }
        }

        stage('Success') {
            steps {
                echo 'Rock Paper Scissors project built successfully.'
            }
        }
    }
}