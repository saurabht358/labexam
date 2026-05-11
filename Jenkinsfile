pipeline {
    agent any


    stages {

        stage('Checkout') {
            steps {
                git branch: 'master', url: 'https://github.com/saurabht358/labexam.git'
            }
        }

        stage('Build and Deploy') {
            steps {
                echo Project Building...
            }
        }

         
    }
}