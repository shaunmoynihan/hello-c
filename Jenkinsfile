pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'make hello'
      }
    }
    stage('Test') {
      steps {
        sh 'make test'
      }
    }
  }
}