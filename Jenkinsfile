pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                echo 'build'
            }
        }
        stage('test') {
            steps {
                echo 'test'
            }
        }
        stage('deploy') {
            steps {
                echo 'deploy'
            }
        }
    }
    post{
        always{
            emailext body: 'some body', subject: 'somesubject', to: 'shwetajs.lrn@gmail.com'
        }
    }
}
