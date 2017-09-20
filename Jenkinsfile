pipeline {
//Pipeline

agent any
 triggers { cron('*/15 * * * *') }
//parameters {
//        choice(
//            choices: 'prakashul-staging\nprakashul-qa',
//            description: '',
//            name: 'REQUESTED_ACTION')
//}


    stages {

        stage ('Workspace Cleanup') {
          steps {
              deleteDir()
    	         }
                                    }

    	stage ('SCM Checkout') {
		steps {
			sh 'echo Pulling code'
			sh 'sleep 15'
  	   		}

			}
	stage ('Build') { 

	steps {
			sh 'echo Building Code'
			sh 'sleep 15'

		}
		}

}

}
