pipeline {
    agent any 
    stages {
	stage('Code Checkout') {
            steps {
                echo 'Check Out code from SCM' 
            }
        }    
        stage('Code Analysis') {
            steps {
                echo 'Code Analysis updated' 
            }
        }		
        stage('Unit Testing') {
            steps {
                echo 'Unit Testing' 
            }
        }
	stage('Security Scanning') {
            steps {
                echo 'Security Vulnerability Scanning' 
            } 
	}
	stage('Packaging') {
            steps {
                echo 'Building Jar file' 
            }
        }
        stage('Dockerization') {
            steps {
                echo 'Building docker image' 
            }
        }
	stage('Deploy') {
            steps {
                echo 'Deploying to K8s'     
            }
        }
    }
}
