pipeline {
  agent {
    node {
      label 'master'
    }
    
  }
  stages {
    stage('gradle build') {
      steps {
        sh './gradlew appdemo demoapp'
      }
    }
  }
}