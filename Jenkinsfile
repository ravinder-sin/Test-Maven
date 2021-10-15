pipeline {
    agent any

          tools
    {
       maven "Maven"
    }
 stages {
      stage('checkout') {
           steps {

                git branch: 'master', url: 'https://github.com/ravinder-sin/Test-Maven.git'

          }
        }
         stage('Execute Maven') {
           steps {

                sh 'mvn package'
          }
        }
        }
        }
