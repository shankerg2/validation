pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                tar -cvf output.tar .
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
