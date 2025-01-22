pipeline {

    agent any

    stages {

        stage('Fetch code') {

            steps {

                git branch: 'main', url: 'https://github.com/rohityadavronit/rohit-testrepo1.git', fetch: 'git fetch --tags --force --progress --timeout 60'

            }

        }

    }

}
