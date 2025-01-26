pipeline
{
    agent any
    stages
    {
        stage("GIT checkout")
    {
    steps{git 'https://github.com/pradyumn12j/mavenproject.git'}}

    stage('test'){
        steps{
            sh 'npm test'
        }

    }

    }

}

