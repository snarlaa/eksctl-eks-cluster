//Declarative Style//

pipeline {
    agent any
 
    options {
        //ansiColor('xterm')
        timestamps()
    }


    stages {
        
        stage("EKS cluster create") {
          steps {
              script {
               sh '''
                    eksctl create cluster -f eks-cluster.yaml
                   '''
            } //Script
          }  //steps
        } //Stage 
       
    } //All stages     
} //Pipeline
