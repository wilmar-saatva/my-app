pipeline {
    agent any
    stages {
        stage('---clean---') {
            steps {
                sh "echo this is the clean stage"
            }
        }
        stage('--test--') {
            steps {
                sh "echo this is the test stage"
            }
        }
        stage('--package--') {
            steps {
                sh "this is the package stage"
            }
        }
    }
}
