pipeline {
    
    stages {
        
        stage("compilacion") {
        
            steps {
                echo "voy a compilar"
                echo "estoy en ello"
                echo "listo"
            }
        
            post {
                succes {
                    echo "solo si los steps ok"
                }
                failure {
                    echo "solo si steps ko"
                }    
                always {
                    echo "siempre"
                }
            }
        }
    }
}