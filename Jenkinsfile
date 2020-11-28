pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name sg --template-body file://security-group.json --region 'us-east-1'"
              }
             }
            }
            }
