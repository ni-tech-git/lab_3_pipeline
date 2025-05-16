pipeline {
    agent any
    stages {
        stage('pwd'){
            steps {
                sh "pwd"
                }
        }
        stage('touch'){
            steps {
                sh "touch lab_3_pipeline.txt"
            }
        }
        stage('echo'){
            steps {
                sh "echo "This is a text file for the lab 3 pipline" > lab_3_pipeline.txt"
            }
        }
        stage('ls'){
            steps {
                sh "ls -a"
            }
        }
        stage('mv'){
            steps {
                sh "mv lab_3_pipeline.txt renamed_lab_3_pipeline.txt"
            }
        }
    }
}        