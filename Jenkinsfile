pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                retry (3) {
                bat 'echo test'
                }
            }
        }
    }
}
