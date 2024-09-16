pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                git branch: 'development', url: 'https://github.com/aamirpatel/GeneralSpringBootProgExce.git'
             
            }
        }
        
         stage('Test') {
            steps {
               echo "Test"
             
            }
        }
    }
}
