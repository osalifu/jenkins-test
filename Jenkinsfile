pipeline {
  agent {
    docker {
      image 'maven:alpine'
    }
    
  }
  stages {
    stage('Initial') {
      steps {
        sh 'mvn -v'
      }
    }
  }
}