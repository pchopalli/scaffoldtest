# scaffoldtest
Repo for practicing Python Scaffold 
Key steps:
* Create Makefile, requirments.txt, python code file, create python test file.
# touch Makefile
* Generate the public and private key
# ec2-user:~/environment $ ssh-keygen -t rsa
* Print/show the public key
# ec2-user:~/environment $ cat /home/ec2-user/.ssh/id_rsa.pub
* Copy the key and maintain it in Github settings
* Git clone enter 'yes'
# ec2-user:~/environment $ git clone git@github.com:pchopalli/scaffoldtest.git
* Create a Virtual environment in home directory
# python3 -m venv ~/.yourenv
* Activate the environment
# source ~/.scaffold/bin/activate
