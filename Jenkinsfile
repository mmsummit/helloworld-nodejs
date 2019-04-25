pipeline {
  agent { label 'nodejs-app' }
  stages {
    stage('Test') {
      steps {
        checkout scm
        container('nodejs') {
          echo 'Hello World!'   
          sh 'node --version'
        }
      }
    }
  }
}
