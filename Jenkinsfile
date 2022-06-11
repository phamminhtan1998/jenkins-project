pipeline {

    agent any;
    stages{
            stage ("build"){
                steps {
                        echo "Build code";
                        echo "Test";
                    }
            }
            stage ("docker"){
                steps {
                    echo "docker build image";
                }
            }

            stage("k8s"){

                steps {
                    echo "kubectl apply -f test";
                }
            }
    }
}