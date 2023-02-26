pipeline{
    
	agent any

	
    stages{
        stage('git checkout'){
            steps{
                git branch: 'main', url: 'https://github.com/rajdeepsingh642/ci-sonar-nexus-project.git'
            }
        }
        
        stage('BUILD'){
            steps {
                script{
                   sh 'mvn clean package'
            }
        }
        }

    }


    }



