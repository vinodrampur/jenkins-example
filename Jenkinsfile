pipeline {
    agent any

    stages {
        stage ('Compile Stage') {

            steps {
                
                    sh 'mvn clean install'
            }
        }
        stage ('Testing Stage') {

            steps {
               
                    sh 'mvn test'
            }
        }
        stage ('Deployment Stage') {
            steps {
            
                    sh 'mvn deploy'
            }
        }
    }
}
