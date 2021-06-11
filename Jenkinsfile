pipeline { 
    agent any  
    stages {
        stage('Compile') { 
            steps { 
               echo 'complied successfully'
                input ('want to proceed')
            }
        } 
        stage('Deploy') {
            steps {
                echo 'deployed successfully'
            }
        }
    }
}
