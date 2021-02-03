pipeline {
  agent any
  stages {
    stage('Test') {
      steps {
        sh 'echo "this is a step"'
      }
    }

    stage('UAT') {
      steps {
        sh 'echo "yeah uat wala step hay!"'
      }
    }

    stage('prod') {
      steps {
        timestamps() {
          echo 'prod mein deployment'
        }

      }
    }

  }
}