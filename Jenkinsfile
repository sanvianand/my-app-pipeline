pipeline {
    agent any 
    stages {
        stage('...clone...') { 
            steps {
                sh "mvn clean" 
            }
        }
        stage('deploy') { 
            steps {
                sh "mvn test"
            }
        }
        stage('test') { 
            steps {
                sh "mvn package" 
           }
        }
    }
}
