pipeline {
    agent any
        stage('Build Bundle') {
           
            steps {
                echo 'Building'
                script {
                    
                    sh "./gradlew bundle${VARIANT}"
                }
            }
        }
