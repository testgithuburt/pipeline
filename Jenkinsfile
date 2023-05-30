pipeline {
  agent any
  stages {
    stage('dev') {
      parallel {
        stage('dev') {
          steps {
            echo 'development stage'
          }
        }

        stage('test') {
          steps {
            echo 'testing stage'
          }
        }

        stage('build stage') {
          steps {
            echo 'building stage'
          }
        }

        stage('deploy') {
          steps {
            echo 'deployment stage'
          }
        }

        stage('prodution') {
          steps {
            echo 'production stage'
          }
        }

      }
    }

  }
}