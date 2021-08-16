pipeline {
  agent {
    node {
      label 'linux-one'
    }

  }
  stages {
    stage('git scm') {
      steps {
        build 'mvn clean install'
      }
    }

  }
}