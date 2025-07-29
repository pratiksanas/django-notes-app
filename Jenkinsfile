@Library('Shared')_
pipeline{
    agent { label 'agent-pratik'}
    
    stages{
        stage("Code clone"){
            steps{
            clone("https://github.com/pratiksanas/django-notes-app.git","main")
            }
        }
        
        // stage("Code Build"){
        //     steps{
        //     docker_build("notes-app","latest")
        //     }
        // }
        // stage("Push to DockerHub"){
        //     steps{
        //         docker_push("dockerHubCreds","notes-app","latest")
        //     }
        // }
        // stage("Deploy"){
        //     steps{
        //         deploy()
        //     }
        // }
        
    }
}
