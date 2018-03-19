pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        emailext(subject: 'test', body: 'test', to: 'tomp@moravia.com')
      }
    }
  }
}