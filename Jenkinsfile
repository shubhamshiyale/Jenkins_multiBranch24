pipeline{
	agent{
		node{
		label "DEV"	
		}
	}

            stages{
               stage ('git-checkout'){
                                   steps{
                                         git "https://github.com/shubhamshiyale/multi-practice.git"
}
}
               stage('mvn') {
			   steps {
			   sh "mvn package"
			   }
			   }
}
}

