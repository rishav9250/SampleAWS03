# SampleAWS03
Question3
3) A company plans to run a monitoring application on an Amazon EC2 instance in a VPC. Connections
are made to the EC2 instance using the instance’s private IPv4 address. A solutions architect needs to
design a solution that will allow traffic to be quickly directed to a standby EC2 instance if the application
fails and becomes unreachable.
Which approach will meet these requirements?
A) Deploy an Application Load Balancer configured with a listener for the private IP address and register the
primary EC2 instance with the load balancer. Upon failure, de-register the instance and register the
standby EC2 instance.
B) Configure a custom DHCP option set. Configure DHCP to assign the same private IP address to the
standby EC2 instance when the primary EC2 instance fails.
C) Attach a secondary elastic network interface to the EC2 instance configured with the private IP address.
Move the network interface to the standby EC2 instance if the primary EC2 instance becomes
unreachable.
D) Associate an Elastic IP address with the network interface of the primary EC2 instance. Disassociate the
Elastic IP from the primary instance upon failure and associate it with a standby EC2 instance.
