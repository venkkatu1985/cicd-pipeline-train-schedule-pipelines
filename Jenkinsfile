pipeline { 
 agent any 
  stages {
   steps {
     echo 'running build'
     sh ' ./gradlew build --no daemon '
     archiveArtifacts artifacts: 'dist/trainSchedule.zip'
     }
     
    }
    }
