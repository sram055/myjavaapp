node{
  stage('SCM Checkout'){
    git 'https://github.com/sram055/myjavaapp'
    }
  stage('Compile-Package'){
    def mvnHome = tool name: 'maven363', type: 'maven'
      
    sh "${mvnHome}/bin/mvn package"
    }
}   
