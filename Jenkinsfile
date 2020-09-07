pipeline {
    agent any
    stages {
        stage("git"){
            steps{
                git credentialsId: 'b18a8ae1-7f6f-4804-be00-d40a45b0da3c', url: 'https://github.com/thanasismoutos/QuotesDB1.git'
            
                echo "QuotesDB.sql"
            }
        }
    }
    
}
