pipeline{
 /* environment{
    registry ="anumishra/department"
   registryCredential = 'docker_id'
    dockerImage =''
  }*/
  agent any{
    statges{
    steps {
                checkout([$class:'GitSCM' , branches:[name:'*/master']],)
      }
    }
     stage('My Message'){
      {
            steps {
                echo 'Hello World'
            }
        }
      
     /* stage('Building our Image'){
        steps{
          script{
          dockerImage = docker.build registry + ":$BUILD_NUMBER"
          }
        }
      }
      stage('Push the image on docker hub'){
        step{
          script{
            docker.withRegistry( '', registryCredential ) {
              dockerImage.push()
            }
        }
      
      }
    }
            stage('Cleaning up') { 
31
            steps { 
32
                sh "docker rmi $registry:$BUILD_NUMBER" 
33
            }
34
            }*/

     
  }
}
