pipeline {
agent { label 'master' }
  options { timestamps () }

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Buid') {
            steps {
                echo 'Building'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing'
            }
        }
        stage('Release') {
            steps {
                echo 'Releasing'
            }
        }
    }
}
