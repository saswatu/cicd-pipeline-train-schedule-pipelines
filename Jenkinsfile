pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
           echo 'Running build automation'
           sh './gradlew build --n0-daemon'
           archiveArtifacts artifacts: 'dist/trainSchedule.zip'
          }
       }
    }
}
