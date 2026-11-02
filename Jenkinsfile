pipeline {
	agent any
	
	stages {
	  stage('Compile') {
		steps {
		  sh 'javac hello.java'
		}
	}
	  stage('Execute & Verfiy') {
		steps {
		  sh 'java hello'
		}
	}
	}
}
		
	
