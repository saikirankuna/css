pipeline {
    agent any

    stages {
        stage('dev') {
            steps {
                echo 'application is building'
            }
        }
         stage('Testing') {
            steps {
                echo 'Automation testing'
            }
        }
         stage('UAT') {
            steps {
                echo 'waiting for UA'
            }
        }
         stage('release') {
            steps {
                echo 'application is ready to release tp production service'
            }
        }
    }
}
