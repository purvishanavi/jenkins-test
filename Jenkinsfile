pipeline {
    agent any

    stages {
        stage('Sonar Scan') 
        {
            steps {
                echo 'Sonar Scan Started...'
                // code for sonar scan 
                echo 'Sonar Scan completed'
            }
        }
        stage('Unit Test') 
        {
            steps {
                echo 'Unit Test Started...'
                // code for Unit Test 
                echo 'Unit Test completed'
            }
        }
        stage('Build Dev') 
        {
            steps {
                echo 'Maven Build Started...'
                echo 'Maven Build completed'
            }
        }
        stage('Test Dev') 
        {
            steps {
                echo ' Test Started...'
                echo 'Test completed'
            }
        }
         stage('Test Build') 
        {
            steps {
                echo ' Build Started'
                echo 'Build completed'
            }
        }
    }
}
