pipeline  { 
  agent any
  tools {
   maven 'Mavan'
  }
stages {
stage ('Initialize') {
  steps {
  sh '''
          echo "PATH = $(PATH)"
          echo "M2_HOME = $(M2_HOME)"
     '''    
  }
 }
  stagr('Build') {
  sh 'mvn clean package'
  }
 }
}
