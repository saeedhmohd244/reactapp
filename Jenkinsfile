pipeline {
    agent any

    stages {
        stage('git checkout ') {
            steps {
               git changelog: false, credentialsId: 'githu', poll: false, url: 'https://github.com/saeedhmohd244/reactapp.git'
            }
        }
    }
}
