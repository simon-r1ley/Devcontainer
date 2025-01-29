# Devcontainer
Cloud-init CI/CD - Development Container DevOps



Primary use case: DevOps automation example build using Docker in VS code. The main aim for the project is to build out a cloud-init testing platform that will aid in the build, test and deployment of cloud init configurations in a docker environment using a Jenkins pipeline. This will be a breif example of CI/CD in an isolated environment.

This can be customised further to test other types of code allong the way such as Puppet or any other solution!

This is a mini project that could be used in its own right just for the purpose of testing Cloud-init builds.

Cloud-init will be served from the development pod directly using a basic script initally.

You can install docker on your system and VS code, clone the repository, and build using docker in VS Code with >dev build command.



Docker pods - Same network
  Jenkins Server - Two pipeleins will be used - 1 Python Webserver - 2 Cloud-init
  Jenkins Agent with Docker installed

Development pod - Pod for developing Cloud-init and Python code.
  Python
  Cloud-init Webserver

Cloud-Init Client pod - This will be a built and run as part of the Jenkins pipeline.
  Client pod for running cloud init



