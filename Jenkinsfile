pipeline{

  agent any

  stages{

    stage('Resore'){

        steps{

         bat 'dotnet restore'
        
        }
    
    }


    stage('Build'){
    
      steps{

        bat 'dotnet build --no-restore'
      
      }
    
    }

    stage('Test'){

       steps{

         bat 'dotnet test --no-build'
       
       }
    
    }
  
  
  }



}
