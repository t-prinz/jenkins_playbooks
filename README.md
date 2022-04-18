# Jenkins playbooks

## References:

* https://www.jenkins.io/doc/book/installing/linux/
* https://www.redhat.com/sysadmin/install-jenkins-rhel8

## Install Jenkins

ansible -i your-inventory install_jenkins.yml

Be sure to capture the initial password

## Perform initial configuration

* Navigate to http://your-server.example.com:8080
* Login with the initial password
* Select Install suggested agents
* Complete the process to Define admin user
