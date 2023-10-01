pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            sh 'cd yaya'
          }
        }

        stage('Build2') {
          steps {
            echo 'Build'
          }
        }

      }
    }

    stage('Test') {
      steps {
        sh 'cd ahmed'
      }
    }

    stage('Last') {
      steps {
        echo 'Last'
      }
    }

  }
}