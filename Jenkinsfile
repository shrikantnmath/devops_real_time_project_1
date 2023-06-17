pipeline {
    agent any
    environment {
      PATH = "$PATH:/opt/apache-maven-3.9.2/bin"
    }
    
    stages {

        stage('CLEAN WORKSPACE') {
            steps {
                cleanWs()
            }
        }

        stage('CODE CHECKOUT') {
            steps {
                git 'https://github.com/shrikantnmath/devops_real_time_project_1.git'
            }
        }
              
    }
}      
