node{
	
		stage('---CLEAN--'){
			git config --global --unset-all remote.origin.proxy
			git 'https://github.com/thogeti/Groovy.git'
		//	sh "mvn clean"
			
		}
		stage('---Packeage--'){			
			def mvnHome=tool name: 'Maven', type: 'maven'
			echo ${mvnHome}
			//sh '${mvnHome}/bin/mvn package'
			
		}
	
	
}
