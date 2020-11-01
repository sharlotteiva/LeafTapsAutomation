pipeline {
  agent any
  stages {
    stage('Git pull code from repo') {
      steps {
        echo 'Git pull code from repo'
      }
    }

    stage('Print Smoke Tests') {
      steps {
        echo 'Print Smoke Tests'
      }
    }

    stage('Certify !!') {
      when {
        branch 'master'
      }
      steps {
        echo 'Build Certified'
      }
    }

  }
}