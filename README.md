# Cloud_Engineering-DevOps-Tech-Challenge
# Challenge 1: 3 Tier Environment using AWS
The script I provided is intended to be used in a shell environment with the AWS Command Line Interface (CLI) installed and properly configured with your AWS credentials. Here's how you can use the script:

Prerequisites:

Make sure you have the AWS CLI installed on your local machine or an AWS EC2 instance.
Configure the AWS CLI with your AWS credentials using aws configure.
Modify Script:

Replace all placeholders (e.g., YOUR_VPC_ID, YOUR_WEB_AMI_ID, YOUR_KEY_PAIR_NAME, etc.) with your actual values. Each placeholder represents a specific AWS resource or configuration.
Run the Script:

Save the script in a file, for example, create_3tier_environment.sh.
Make the script executable with the command: chmod +x create_3tier_environment.sh.
Execute the script with: ./create_3tier_environment.sh.

The script will create a 3-tier environment in your AWS account, including VPC, subnets, security groups, EC2 instances for web and application tiers, and an RDS database instance for the data tier. It will also configure security groups and other essential settings.

Please be cautious when running scripts that create AWS resources, and ensure that you understand the implications and costs associated with the resources being created. It's recommended to test such scripts in a sandbox or non-production environment first.




# Challenge 2: Code that will query the meta data of an instance within AWS environment and provide a json formatted output.

To query the metadata of an EC2 instance within AWS and provide a JSON-formatted output, you can use the instance metadata service provided by AWS. The metadata service is accessible from within an EC2 instance, and it provides information about the instance itself. 

Save the script (get_instance_metadata.sh) to a file, make it executable, and run it with the desired key as an argument. It will retrieve the specified key and format it as a JSON object.

That's it! You now have a way to query the metadata of an AWS EC2 instance and format the output as JSON, with the bonus ability to retrieve specific data keys individually.


# Challenge 3: Nested Object Value Retrieval

Save the script to a file (extract_value.sh), make it executable using chmod +x extract_value.sh, and then run it. It will parse the nested objects and return the values associated with the specified keys.











