pipeline {
    agent buildserver
    stages {
        stage('checkout') {
            steps {
                sh 'echo "Hello World"'
                sh '''
                    echo "Multiline shell steps"
                    ls –lah
                '''
            }
        
        stage ('build'){
    }
}
