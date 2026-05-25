pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo 'Compilando aplicación...'
                sh 'echo Build completado correctamente'
            }
        }

        stage('Test') {
            steps {
                echo 'Ejecutando pruebas...'
                sh 'echo Pruebas ejecutadas correctamente'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Desplegando aplicación...'
                sh 'echo Aplicación desplegada correctamente'
            }
        }
    }
}