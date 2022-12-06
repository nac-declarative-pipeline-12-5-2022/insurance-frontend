pipeline {
  agent none
  stages {
    stage('Say Hello') {
      agent { label 'node-js app' }
      steps {
        echo 'Hello World!'   
        sh 'java -version'
      }
    }
  }
}

