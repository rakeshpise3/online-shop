node{

    stage('SCM Checkout')
    {
       git branch: 'dev', url: 'https://github.com/rakeshpise3/online-shop.git'
    }
    
    stage('Run Docker Compose File')
    {
        sh 'sudo docker-compose build'
        sh 'sudo docker-compose up -d'
    }
  
}
