pipeline {
  agent {
    node {
      label 'maven:3-alpine'
    }

  }
  stages {
    stage('') {
      steps {
        sh 'mvn -B -DskipTests clean package'
      }
    }

  }
}