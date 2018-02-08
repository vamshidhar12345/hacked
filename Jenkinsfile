pipeline {
agent any
stages {
stage ('Compile Stage') {
steps {
bat 'mvn clean compile'
}
}
stage ('Testing Stage') {
steps {
bat 'mvn test'
}
}
stage ('Installing Stage') {
steps {
bat 'mvn install'
}
}
  stage ('deploying stage'){
    steps{
     bat 'mvn deploy'
    }
}
} 
