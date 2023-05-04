# tuned-software

Step-1) Open the terminal on your Linux system.

Step-2) Install Tuned software by running the following command:

           sudo yum install tuned
					 
     2a) If you're using CentOS 8 or RHEL 8, use the following command instead:
     
           sudo dnf install tuned
	
Step-3) Once Tuned software is installed, start the Tuned service and set it to run at boot by running the following commands:

           sudo systemctl start tuned
           sudo systemctl enable tuned
	
Step-4) To check the status of the Tuned service, run the following command:

           sudo systemctl status tuned               #If the service is running, you should see a message indicating that Tuned is active.
	
Step-5) You can then use the Tuned command-line tool to manage Tuned profiles and optimize your system's performance. To see a list of available Tuned profiles, run the following command:

           sudo tuned-adm list
	
This will show you a list of profiles that you can use to optimize your system for different types of workloads.

That's it! With Tuned software installed and running, you can optimize your Linux system's performance and improve your productivity.
        

         
