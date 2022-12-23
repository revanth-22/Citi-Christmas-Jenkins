pipeline {
  agent any
    stages{
      stage('Checkout github repositary master') {
        steps {
            git branch: 'master',
	    url: 'https://github.com/revanth-citibank/Citi-Christmas-Jenkins.git'
            sh "ls -lat"
      }
    }

 }  
}
