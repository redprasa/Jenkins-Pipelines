pipeline {
	agent {
	node {
	label 'master'
}
}
	stages {
		stage('git_clone'){
			steps {
			sh '''
			rm -rf Jenkins-Pipelines 
			git clone 'https://github.com/redprasa/Jenkins-Pipelines.git'
			'''
}
}
		stage('build'){
			steps {
			sh '''
			echo "write here maven or shell script commands"
			'''
}
}
        stage('sonar'){
			steps {
			sh '''
			echo "write here sonar configurations"
			'''
}
}
}
}
