pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            sh 'echo $pwd'
          }
        }

        stage('Test') {
          steps {
            echo 'Hello World'
          }
        }

      }
    }

  }
}