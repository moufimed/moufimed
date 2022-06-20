pipeline {
    agent { docker { image 'ruby:3.0.3-alpine' } }
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World"'
		sh 'ruby --version'
            }
        }
    }
}
