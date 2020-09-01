pipeline{
    agent{
        docker{
            image "maven:3.6.0-jdk-13"
            label "docker"
        }
    }
    // agent any
    // tools{
    //     maven "3.6.3"
    // }
    stages {
        stage("Build") {
            steps {
                echo 'Hello first pipeline'
                sh "mvn -version"
            }
        }
    }
}