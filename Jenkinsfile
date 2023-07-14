pipeline {
  agent any;
  stages {
      stage ("checkout code") {
        steps {
          git 'https://github.com/riteshakadu/webapp-demo.git'
        }
      }
      stage ("build code") {
        steps {
          sh "mvn package"
        }
      }
  }
}
