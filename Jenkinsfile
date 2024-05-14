pipeline {
    agent any

    stages {
        stage('Print Commit ID') {
            steps {
                script {
                    echo "Commit ID: ${scm.revision}"
                }
            }
        }
    }
}
