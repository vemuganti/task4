properties([[$class: 'GithubProjectProperty',
             displayName: '', 
             projectUrlStr: 'https://github.com/vemuganti/Task4.git/'], 
             pipelineTriggers([])])

pipeline {
    agent any
    stages {
        stage('Example') {
            steps {
                echo 'Hello World'
            }
        }
    }
    post { 
        always { 
            echo 'I will always say Hello again!'
        }
    }
}
