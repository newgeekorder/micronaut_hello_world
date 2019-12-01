//#!groovy
////@Library('jenkins-enterprise@master')
import java.lang.Object

node {
    checkout scm
     stage('Build') {
               steps {
                   script {
                           sh './gradlew build --no-daemon' //run a gradle task
                   }
               }
           }
}


//buildApplication {
//    notifySteps = [new FooNotifituer()]
//}
//
//class FooNotifituer {
//
//    def call(def script){
//        script.echo "doing work"
//    }
//
//}