pipeline {
    agent any 
    stages {
        stage('---clean---') { 
            steps {
                sh "mvn clean test" 
		
            }
        }
        stage('---Test---') { 
            steps {
                sh "mvn test" 
            }
        }
        stage('---package---') { 
            steps {
                sh "mvn package" 
            }
        }
    }
}
