pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'Successful build!'
          }
        }

        stage('Test') {
          steps {
            echo 'Tests are passed!'
          }
        }

      }
    }

    stage('Deploy') {
      steps {
        echo 'App is deployed!'
      }
    }

  }
}