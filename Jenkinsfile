node() {

    stage ('Checkout') {
        sh 'echo Checkout'
        git url:"https://github.com/yunqiangwu/spring-cloud-study.git"
    }

    stage ('Create Virtualenv') {
        sh 'ls ../ -la'
    }

    stage ('Build') {
        sh 'mvn clean package'
    }

}