# Cloud Infrastructure Project

This repo serves as the template for Project 2 of the CyberND.

## Project Initial Launch

* Clone the project - `git clone https://github.com/udacity/CyberND_Project_2.git`
* Create a file called `terraform.tfvars` and add your access key and secret key for your proper AWS IAM user like so:

```
access_key = "YOUR_ACCESS_KEY"
secret_key = "YOUR_SECRET_KEY"
```

* Run it = `./launch.sh`

Load balance endpoint = project-2-loadbalancer-534438265.us-west-2.elb.amazonaws.com
Webserver A address = 10.0.1.182
Webserver B address = 10.0.2.55
Zone A Bastion = ec2-54-200-214-88.us-west-2.compute.amazonaws.com
Zone B Bastion = ec2-34-221-19-254.us-west-2.compute.amazonaws.com

ssh -i udacity_student2.pem ubuntu@ec2-34-217-62-27.us-west-2.compute.amazonaws.com

127.0.0.1       localhost.localdomain   localhost       ec2-34-217-62-27.us-west-2.compute.amazonaws.com