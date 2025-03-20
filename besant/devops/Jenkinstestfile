pipeline {
    agent any
    stages {
        stage("print") {
            steps {
                sh 'echo "Good morning" >> output'
                sh 'mv output kishor'
            }
        }
        stage("clone") {
            steps {
                git 'https://github.com/viswkum/devops-84a.git' 
            }
        }
    }
}
