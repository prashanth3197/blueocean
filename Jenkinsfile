pipeline {
  agent any
  stages {
    stage('build') {
      parallel {
        stage('build') {
          steps {
            echo 'build'
          }
        }

        stage('parallel') {
          steps {
            echo 'parallel '
          }
        }

      }
    }

    stage('test') {
      steps {
        echo 'test'
      }
    }

    stage('deploy') {
      steps {
        echo 'deploy'
      }
    }

  }
}