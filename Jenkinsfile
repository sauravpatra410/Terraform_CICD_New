node {
    
    stage('tf init') {
        sh 'terraform init'
    }
    stage('tf plan') {
        sh 'terraform plan'
    }
    stage('tf apply') {
        sh 'terraform apply -auto-approve'
    }
}
