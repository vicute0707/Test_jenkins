pipeline{
    agent any
    stages{
        stage('Git clone'){
            steps{
                echo "Đang clone dữ liệu về nhé.!!"
            }
        }
        stage('Maven Build'){
            steps{
                sh 'mvn clean package -DskipTests'
            }
        }
        stage('Docker Build Image'){
            steps{
                echo "Đang build docker image từ docker file"
            }
        }
        stage('Maven Deploy'){
            steps{
                echo "Đang trong quá trình deploy dự án lên môi trường dev"
            }
        }
    }
}
