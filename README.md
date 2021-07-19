# CloudformationTask01
This template deploys a VPC, with a pair of public and private subnets spread
across two Availability Zones. It deploys an internet gateway, with a default
route on the public subnets. It deploys a pair of NAT gateways (one in each AZ),
and default routes for them in the private subnets. It also provide scalibilty and high availability by implementing Auto scaling group and Load Balancer.

Please refer to below system architecture!
