pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh '''echo \'1\'
'''
        sh 'echo \'2\''
      }
    }

    stage('test1') {
      steps {
        sh 'echo \'3\''
      }
    }

  }
}