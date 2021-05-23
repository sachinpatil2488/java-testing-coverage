pipeline {
    agent { label 'master' }
    stages {
	stage('build') {
            steps {
               sh 'mvn clean package'
            }
        }
	stage('test'){
	    steps {
		sh 'mvn test'
	    }
	}
    }
}
