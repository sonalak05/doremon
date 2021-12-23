node{
    stage("build"){
        echo "building the project"
    }
    stage("test"){
        echo "testing the project"
    }
    stage("deploy"){
        echo "deploying the project"
    }
    
}
