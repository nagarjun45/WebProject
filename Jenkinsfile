pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                // sh 'who iam i'
                sh  'scp -i "nagarjun.pem" -o StrictHostKeyChecking=no index.html ubuntu@ec2-54-160-250-82.compute-1.amazonaws.com:~/var/www/html/WebProject/'
                // sh 'cp index.html /var/www/html/WebProject/' 
            }
        }
    }
}