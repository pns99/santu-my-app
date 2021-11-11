node {
    stage ("SCM Checkout") {
	 	   git 'https://github.com/pns99/santu-my-app.git'
    }
    stage ("Compile-package") {
	    //mvntest
	//def mvnHOME = tool name: 'mymaven', type: 'maven'
        sh "/opt/maven/bin/mvn package"
    }
}
