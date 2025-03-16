pipeline {
    agent any

    stages {
        stage ('changing the file permission') {
            steps {
                sh ' chmod +x script.sh'
            }
        }

        stage ('executing the file') {
            steps {
                sh './script.sh'
            }
        }
    }
}
