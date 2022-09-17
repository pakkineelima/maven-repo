pipeline {
  agent any
  tools {
    maven 'null' 
  }
  stages {
    stage ('Build') {
      steps {
        sh 'mvn clean package'
      }
    }
  }
}
