pipeline {
  agent any
  stages {
    stage('') {
      steps {
        sh '''apic publish uinames-product_2.0.0.yaml --catalog sb --organization esustglobalapiscoe --server apim
'''
      }
    }
  }
  environment {
    Desarrollo = 'Dev'
    Local = 'Sandbox'
  }
}