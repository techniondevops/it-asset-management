pipeline {
  agent any
  stages {
    stage('Stage1') {
      steps {
        sh '''whoami
pwd'''
        sleep 5
      }
    }

    stage('stage2') {
      steps {
        echo 'Hello, We are done'
      }
    }

  }
}