pipeline {
  environment {
    imagename = "opeomotayo/jenkinsfile-test"
    registryCredential = 'dockerhub-test'
    dockerImage = ''
  }
  agent any
  stages {
    stage('Cloning Git') {
      steps {
 //       git([url: 'https://github.com/opeomotayo/test-jenkinsfile.git', branch: 'master', credentialsId: 'ismailyenigul-github-user-token'])
 	checkout scm

      }
    }
    stage('Building image') {
      steps{
     
      sh "echo Hey Jenkinsfile && sleep 10"


          }
      }
   
    
    
  }
}
