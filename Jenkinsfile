pipeline{
    agent any
    tools{
        maven 'maven'
    }
    stages{
        stage('with using env'){
            steps {
                echo "$JOB_NAME"
                echo "$BUILD_ID"
        }
        }
    }
