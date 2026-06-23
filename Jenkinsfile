pipeline{
    agent{
        label any 
    }
    stages{
        stage("Install Dependencies"){
            steps{
                bat "npm install"
            }
        }
        stage("Test"){
            steps{
                bat "npm test"
            }
        }
    }
}