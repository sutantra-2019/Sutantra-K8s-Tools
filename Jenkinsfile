pipeline{
  agent any
  stages{
    stage('Check Kubectl'){
      steps{
        sh "kubectl version"
      }
    }
    stage('Check Helm'){
      steps{
        sh "helm version"
      }
    }
  }
}
