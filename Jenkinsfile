pipeline {
    agent any

    stages {
        stage('Deploy') {
            steps {
                 sh '''
                   chmod +x destroy.sh
                   ./destroy.sh
                    '''
            }
        }

    }

}
