pipeline{
  agent any
  stages{
    stage('Deploy')
          {
            steps{
              echo "Test succesfull"
              bat "mvn compile"
            }
          }
    stage('Build')
          {
            steps{
              echo "Build succesfull"
              bat "mvn clean"
            }
          }
    stage{'Test')
          {
            steps{
              echo "Test succesfull"
              bat "mvn test"
            }
          }
         }
  }

  
  
