pipeline{
  agent any
  stages{
    stage{
      steps{
        echo "Running build automation"
        sh "./gradlew build --no-deamon"
        archiveArtifacts artifacts: 'dist/trainSchedule.zip'
      }
    }
  }
}
