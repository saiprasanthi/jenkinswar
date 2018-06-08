pipeline {
  agent any
  stages {
    stage('checkout') {
      steps {
        git(url: 'https://github.com/saiprasanthi/jenkinswar.git', branch: 'master', credentialsId: 'saiprasanthi')
      }
    }
  }
}