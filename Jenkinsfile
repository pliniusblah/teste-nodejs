pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
		sh 'pwd'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
		sh 'rm -rf node_modules'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
