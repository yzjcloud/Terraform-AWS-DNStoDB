# Terraform-AWS-DNStoDB

- version.tf
- general variables
- local values (common tags)
- datasource (define ami/device type)
- VPC (variables/modules/output， subnet-public/private/database)
- security group (variables, output, SG-bastion/private/loadbalancer/rdsdb)
- router53 (get DNS infromation）
- EC2 (variables, bastion, private, output)
 /*** private host may need put dependencies of VPC, if need to connect to the Internet***/
- elastic IP resource (dependencies on ec2/vpc)
- null resource (optional)
- ALB (variables, module, outputs)
- ACM （create/verify SSL certificates)
- DNS registration
- RDS DB （variables - name/DB id/username/password, module, output)
- .tfvars 
- script
