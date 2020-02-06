pipeline {
   agent any
   stages {
     stage {'build'} {
      steps {
        echo "build automation"
	sh './gradelw build --no--daemon'
	archiveArtifacts artifacts: 'dist/trainSchedule.zip'
	}
      }
    }
   }


