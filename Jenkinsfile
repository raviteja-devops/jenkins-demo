pipeline {

  agent {
    label 'ansible'
  }

  stages {

    stage('Hello') {
      steps {
        echo 'This Is My Jenkins Job'
      }
    }

  }

  post {
    always {
      echo 'This Is Success'
    }
  }

}