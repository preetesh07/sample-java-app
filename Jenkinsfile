pipeline {
  agent {
    node {
      label 'newnode'
    }

  }
  stages {
    stage('build ') {
      steps {
        sh 'mvn clean package'
      }
    }

  }
}