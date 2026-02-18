node {
    stage('Clone') {
        git branch: 'main', url: 'https://github.com/yacineyacin226-source/jenkins-helloworld.git'   
    } 
    stage('Build') {
            sh 'javac Main.java'
    }
    stage('Run') {
        sh 'java Main.java'
    }
}
