pipeline {
    agent any
    
    stages {
        stage("Prepare") {
            steps {
                echo 'prepare...'
            }
        }

        stage("Start a test image") {
            steps {
                sh "docker run hello-world"
            }
        }
     }
}
