pipeline {
  agent any
  stages {
    stage('Poll') {
      steps {
        git(poll: true, url: 'https://github.com/nghikhoi/carbon-shop', branch: 'main')
      }
    }

  }
}