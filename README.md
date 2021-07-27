mvn-app

# Maven command to create java web project

-----
mvn archetype:generate 
	
    -DgroupId=in.javahome
    
	-DartifactId=mvn-app
    
	-DarchetypeArtifactId=maven-archetype-webapp
	
    -DinteractiveMode=false
  
  -------
### Installing nexus in Linux

sudo yum install java-1.8.0-openjdk -y

   cd /opt/
   
   sudo wget https://download.sonatype.com/nexus/3/latest-unix.tar.gz
   
   sudo tar -xf latest-unix.tar.gz
   
   sudo mv nexus-3.21.1-01/ nexus3
   
   sudo chown -R ec2-user:ec2-user nexus3/ sonatype-work/
   
  ### starting Nexus
   
   /opt/nexus3/bin/nexus start
   
   /opt/nexus3/bin/nexus stop
    
   /opt/nexus3/bin/nexus restart
   
   
