# Demo

## Create AWS cloude
./aws_cloud_formation.sh

## log in to mgmt node
ssh-agent bash
ssh-add pemfiles/sshKey.pem
ssh -i pemfiles/sshKey.pem ubuntu@<public ip of mgmtServer>

## download the bibs from bitbucket
git clone https://rerahim@bitbucket.org/rerahim/bibs.git
