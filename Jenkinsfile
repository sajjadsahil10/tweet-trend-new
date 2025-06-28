pipeline {
    agent {
        node {
            label 'maven'
        }
    }
environment {
    PATH = "/opt/apache-maven-3.9.10/bin:$PATH"
}
    stages {
        stage("clone repository"){
            steps {
                 git branch: 'main', url: 'https://github.com/sajjadsahil10/tweet-trend-new.git'
            }
        }
    }
}