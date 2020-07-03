pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        echo 'Stage checkout from github'
      }
    }

    stage('Build') {
      steps {
        echo 'Build application'
      }
    }

    stage('Testing') {
      steps {
        echo 'Testing application'
      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploy app to production'
      }
    }

  }
}