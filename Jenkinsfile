pipeline {
  agent any
  stages {
    stage('Checkout Code') {
      steps {
        git(url: 'https://github.com/pra-naya/Jenkins-Demo/', branch: 'main')
      }
    }

    stage('Log') {
      steps {
        sh '''ls -la
'''
      }
    }

  }
}