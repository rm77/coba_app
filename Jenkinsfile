pipeline {
    agent { docker { image 'python:3.8' } }
    stages {
        stage('build') {
            steps {
		sh 'echo "Hello World"'
		sh '''
			echo "Multiline"
		'''
                sh 'python --version'
            }
        }
    }
}
