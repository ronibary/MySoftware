properties([pipelineTriggers([pollSCM('*/30 * * * *')])])
node { 

    stage("clone") { 

        git branch: 'master', url: 'https://github.com/ronibary/MySoftware.git' 

    } 

    stage("show files"){ 

        sh "ls -l" 

    } 

} 
