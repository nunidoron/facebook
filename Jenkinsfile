properties([pipelineTriggers([pollSCM('* * * * *')])])
node {
    stage("First"){
       sh """
       ls -l
       echo Hi form git
       """
    }
}
