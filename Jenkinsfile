pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo "Degerli to Reinvent Yourself"
                sh 'echo second step'
                sh 'echo another step'                
                sh '''
                echo 'Multiline'
                echo 'Example'
                '''
                echo 'not using shell'
            }
        }
    }
}