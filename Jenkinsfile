pipeline {
    agent any
     
    
    stages {
        stage('Run and Compile Code') {
             when {
                branch 'main'
            }
            steps {
                echo 'Running build automation'
                
//                 bat "micro-gw init"
                bat "micro-gw build  BalanceInquiryV2 --deployment-config /BalanceInquiryV2/conf/deployment-config.toml"
//                 BalanceInquiry --deployment-config /BalanceInquiry/conf/deployment-config.toml
//               micro-gw build BalanceInquiry --docker --docker-image BalanceInquiry:v1 --docker-base-image wso2/wso2micro-gw:3.2.0
//                 micro-gw build BalanceInquiry --deployment-config /BalanceInquiry/conf/deployment-config.toml
//                 micro-gw build BalanceInquiry --deployment-config /BalanceInquiry/conf/deployment-config.toml  --micro-gw  /BalanceInquiry/conf/micro-gw.conf
//                 archiveArtifacts artifacts: '**/target/*.jar'
            }
        }
        

    }
}
