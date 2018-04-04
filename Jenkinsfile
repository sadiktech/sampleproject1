pipeline {
  agent any
  stages {
    stage('Unit Test') {
      steps {
        sh 'export PATH=/opt/maven/apache-maven-3.5.2:/opt/maven/apache-maven-3.5.2/bin:$PATH && mvn clean test'
      }
    }
 }
}