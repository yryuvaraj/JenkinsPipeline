pipeline {
  agent any
  stages {
    stage('Stage1') {
      parallel {
        stage('Stage1') {
          steps {
            sh 'echo Hello world'
          }
        }
        stage('Stage2') {
          steps {
            sh 'echo Hello world 2'
          }
        }
      }
    }
    stage('Stage 3') {
      steps {
        sh 'echo Hello3'
      }
    }
  }
}