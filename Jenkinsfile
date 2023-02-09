pipeline {
    agent any

    stages {
        stage('clone from github') {
            steps {
                git branch: 'main', url: 'https://github.com/theusersam/jenkins-pipeline.git'
            }
        }
        
    }
}
