pipeline{
  agent{
    label 'slave'
  }
  stages{
    stage('get code from git'){
      steps{
      checkout scm
      }
    }
    stage('copy code'){
      steps{
        sh 'cp /home/jimmy/jenkins/workspace/first-deployment/index.html /var/www/html/index.html'
      }
    }
  }
}
      
  
  
      








