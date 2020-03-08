// Powered by Infostretch 

timestamps {

node () {

	
	stage ('sample nodejs build - Build') {
 	
// Unable to convert a build step referring to "jenkins.plugins.nodejs.NodeJSBuildWrapper". Please verify and convert manually if required.		// Batch build step
bat """ 
npm install 
 """ 
	}
	stage ('actual nodejs build - Build') {
 	
// Unable to convert a build step referring to "jenkins.plugins.nodejs.NodeJSBuildWrapper". Please verify and convert manually if required.		// Batch build step
bat """ 
npm run build
 """ 
	}
	stage ('sample nodejs test - Checkout') {
 	 
// Unable to convert SCM referring to "hudson.plugins.filesystem_scm.FSSCM". Please verify and convert manually if required. 
	}
	stage ('sample nodejs test - Build') {
 	
// Unable to convert a build step referring to "jenkins.plugins.nodejs.NodeJSBuildWrapper". Please verify and convert manually if required.		// Batch build step
bat """ 
echo "shell testing npm"
npm test 
 """ 
	}
}
}
