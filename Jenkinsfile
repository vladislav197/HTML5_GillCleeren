pipeline {
  agent any
  stages {
    stage('StageDemo1') {
      steps {
        echo 'Hello $DEMO'
      }
    }

  }
  environment {
    DEMO = '123'
  }
}