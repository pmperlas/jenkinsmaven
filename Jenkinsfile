pipeline {
  agent {
    dockerfile {
      filename 'Dockerfile'
    }

  }
  stages {
    stage('Test') {
      parallel {
        stage('Test') {
          steps {
            sh 'echo "Test"'
          }
        }

        stage('Test2') {
          steps {
            echo 'hola'
          }
        }

      }
    }

    stage('test3') {
      steps {
        sleep 12
      }
    }

  }
}