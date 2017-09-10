pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'echo HELLO WORLD'
        logstashSend failBuild: true, maxLines: 1000
      }
    }
  }
}
