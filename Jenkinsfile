pipeline {

    agent any

    stages {
        stage('Echo Something') {
           echo 'Something'
        }
    }

    post {
        failure {
            echo 'I echo FAILURE as post action!'
        }
        success {
            echo 'I echo SUCCESS as post action!'
        }
    }

}