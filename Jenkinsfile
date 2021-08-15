properties([parameters([choice(choices: ['SLES15', 'Windows2019'], description: 'testing', name: 'OS')])])

pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo "${params.OS}"
            }
        }
    }
}
