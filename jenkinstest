pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
      sh 'echo "HELLO NICOLE2.0"'
      sh '''
        echo "Thi will list current dir content from latest"
        ls -lh
        '''
      }
    }
    stage ('Test') {
      steps {
      sh 'echo "HELLO TEST2.0"'
      sh '''
        echo "This list current dir2.0"
        pwd
        '''
      }
    }
  }
}
