node {
    stage('clone'){
        git branch: 'main', url: 'https://github.com/ulrichfokoutakoukam/SimpleProject.git'
    }
    stage('build'){
        sh label: 'compile', script: 'javac Main.java'
    }
    stage('run'){
        sh label: 'run', script: 'java Main'
    }
}