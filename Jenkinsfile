def gv

pipeline {
    agent any
    stages {
        stage("build image") {
            steps {
                echo "Building the Images"
            }
        }
        stage("test") {
            steps {
                echo "Testing the Images"
            }
        }
        stage("deploy") {
            steps {
                echo "Deploying the Chart"
            }
        }
    }   
}
