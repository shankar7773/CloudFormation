# CloudFormation

Parameters

VPC CIDR Range
Availability Zone Choices
Subnet CIDR Choices
Instance Name
Instance Type - Forced to t2.micro
KeyName (Picked up from account)
Mappings

Regions - Mapped to us-east-1 and ap-south-1
Resources

VPC
Internet Gateway
Routes and Routing Table for internet traffic
Two subnets [ Public & Private ]
Security Group to allow internet traffic
