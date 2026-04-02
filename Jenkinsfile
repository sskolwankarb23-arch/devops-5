pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo "Building..."
                sh 'echo Build successful'
            }
        }
        stage('Test') {
            steps {
                echo "Testing..."
                sh 'echo Tests passed'
            }
        }
        stage('Deploy') {
            steps {
                echo "Deploying..."
                sh 'echo Deployment done'
            }
        }
    }
}
