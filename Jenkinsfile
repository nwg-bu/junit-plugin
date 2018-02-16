pipeline {
  agent {
    docker {
      image 'maven:3.5.2-jdk-8'
      args '-v /Users/nwg/.m2:/root/.m2'
    }
    
  }
  stages {
    stage('Initialize') {
      steps {
        sh '''echo PATH = ${PATH}
echo M2_HOME = ${M2_HOME}'''
      }
    }
    stage('Build') {
      steps {
        echo 'This is still a minimal pipeline.'
      }
    }
  }
}