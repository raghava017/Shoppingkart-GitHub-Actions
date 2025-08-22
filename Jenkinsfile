pipeline {
    agent any
    
    tools {
        jdk 'jdk11'
        maven 'maven3'
    }

    stages {
        stage('Git CLone ') {
            steps {
<<<<<<< HEAD
                git branch: 'test', url: 'https://github.com/Raghava0684/Shopping-Cart-project.git'
=======
                git branch: 'dev', url: 'https://github.com/Raghava0684/Shopping-Cart-project.git'
>>>>>>> a65e1c1ff007c5d9c04c61011823169ed079f7fe
            }
        }
        
        stage('mvn compile ') {
            steps {
                sh 'mvn clean compile -DskipTests=true'
            }
        }
        
        stage('mvn package ') {
            steps {
                sh 'mvn clean package -DskipTests=true'
            }
        }
        
        
    }

}
