pipeline {
    agent any

    stages {
        stage('Compile') {
            steps {
                echo 'Compiling...'
                bat 'javac --release 8 HelloWorld.java'
            }
        }

        stage('Run') {
            steps {
                echo 'Running...'
                bat 'java HelloWorld'
            }
        }
    }
}

