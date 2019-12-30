#!/bin/bash
yum -y update
yum install -y ruby
yum install -y aws-cli
cd /home/ec2-user
aws s3 cp s3://aws-codedeploy-us-east-2/latest/install . --region us-east-2
chmod +x ./install
./install auto




# aws
Accompanying repository for my YouTube Channel

|YouTube Channel|Playlist|
|-|-|
|[Just Me and Opensource](https://www.youtube.com/c/wenkatn-justmeandopensource)|[AWS Playlist](https://www.youtube.com/watch?v=WAawiM8VPQY&list=PL34sAs7_26wMKAl2wcDXb7ko65V8KDBzG)|
