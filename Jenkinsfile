pipeline{
  agent any
  environment{
       value = "build"
       value2 = "test"
       value3 = "deploye"}
 stages{

     stage('build'){
	  steps{
        echo "$VALUE"
		}
}
     stage('test'){
	  steps{
        echo "$VALUE2"
		}
}
     stage('deploye'){
	  steps{
        echo "$VALUE3"
		}
   }
 }
}