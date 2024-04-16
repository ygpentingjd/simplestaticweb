Install requirement package
yum install httpd php git -y

Running web service
systemctl start httpd && systemctl enable httpd && systemctl status httpd
