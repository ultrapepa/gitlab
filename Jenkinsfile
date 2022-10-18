pipeline {
    agent {label 'mainslave'}

    stages {
        stage('scropt') {
            steps {
            sh 'hadolint Dockerfile'
            }
        }
        
    }
}
