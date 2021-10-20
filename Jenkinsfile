pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh '''#!/usr/bin/env groovy

                    def str = "Hello world"
                    def num = 2
                    // 1) remove an empty line need approved again 2) cannot see approved scripts list
                    // trusted users, regular users
                    def total = num * 10 + 7
                    println str
                    println total
                '''
            }
        }
    }
}
