pipeline {
 agent any
  stages {
     stage ("Build mvn") {
      steps {
       sh  "mvn clean install"
      }
      stage ("create docker image") {
       steps {
       sh "docker image build -t mydockerdemo"
       }
      }
     }
  }
 
}
