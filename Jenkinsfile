pipeline {
    agent any
    triggers {
        githubPush()
    }
    stages {
        stage('VCS') {
            steps {
                git branch: 'main',
                    url: 'https://github.com/srinuNuthi/spring-petclinic.git'
            }
        }
        stage('Check Trigger') {
            steps {
                echo "i am fromb qa repos."
            }
        }
    }
}

