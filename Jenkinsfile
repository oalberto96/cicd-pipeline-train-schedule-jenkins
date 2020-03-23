pipeline {
  agent any
  stages {
    stage('Build'){
      echo 'Building project...'
      sh './gradlew build --no-daemon'
      archiveArtifacts artifacts: 'dist/trainSchedule.zip'
    }
  }
}
