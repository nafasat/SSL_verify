pipeline {
  agent none
  stages {
    stage('mastercopy') {
      agent {
        node {
          label 'node-02'
        }

      }
      steps {
        sh '''#!/bin/bash

echo "your system hostname is $HOSTNAME"
exit 0'''
      }
    }
  }
}