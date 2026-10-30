# Cloud-Storage-creation-S3-and-Launching-an-EC2-Instance-in-AWS
Ex.2 Cloud storage creation (S3) and launching an (Ec2) instance in AWS
Aim:
To create a Simple Storage Service (S3) in AWS and to launch an EC2 instance in AWS. 
Procedure
a)	Steps to Create a first S3 Bucket:
Step 1: Sign in to the AWS Management Console
Go to https://console.aws.amazon.com/s3.
Step 2: Open the S3 Service
In the console, type S3 in the search bar and select S3 to open the service dashboard.
Step 3: Create Bucket
Click the Create bucket button.
Step 4: Configure Bucket Settings
•	Bucket name: Choose a globally unique name.
•	AWS Region: Select the region where you want to store your data.
Step 5: Object Ownership
Choose between:
	ACLs disabled (recommended) – Bucket owner has full control.
	ACLs enabled – Control access via access control lists.
Step 6: Block Public Access Settings
By default, all public access is blocked. Leave it as-is unless you need public access.
Step 7: Bucket Versioning (optional)
Choose whether to enable versioning for objects in the bucket.
Step 8: Encryption (optional)
Select encryption options (SSE-S3, SSE-KMS, or none).
Step 9: Advanced Settings (optional)
Add tags, configure logging, etc.
Step 10: Create the Bucket
Click Create bucket at the bottom of the page.
b)	i. Steps to launch an EC2 Instance
1.	Go to the EC2 Dashboard in AWS Console.
2.	Click on “Launch Instance”.
3.	Choose an Amazon Machine Image (AMI) (e.g., Amazon Linux).
4.	Select an instance type (e.g., t2.micro for Free Tier).

5.	Create or choose a key pair for SSH access.
6.	Configure network settings (use default VPC/subnet).
7.	Configure storage (default root volume is fine).
8.	Review the settings and click “Launch Instance”.
9.	Wait for the instance to enter the running state.

c)	Step 3: Connect to Your Instance
•	Linux: Use SSH command with your .pem key.
•	Windows: Use RDP with decrypted admin password.

d)	Steps to Clean Up (Terminate the Instance)
1.	Go to EC2 Instances.
2.	Select your instance → Instance State → Terminate.


Snap Shots:


<img width="1920" height="1080" alt="Screenshot 2026-10-29 160059" src="https://github.com/user-attachments/assets/55fa65ea-4b68-4fb9-9093-2cb59dd2366f" />
<img width="1920" height="1080" alt="Screenshot 2026-10-29 160050" src="https://github.com/user-attachments/assets/4cd41dd8-0a4a-4eaf-9f67-152236033ac7" />
<img width="1920" height="1080" alt="Screenshot 2026-10-29 155559" src="https://github.com/user-attachments/assets/ee1bdb66-0090-491e-86bb-6dde7bb6fd26" />
<img width="1920" height="1080" alt="Screenshot 2026-10-29 155055" src="https://github.com/user-attachments/assets/fba490ba-660c-4d55-8295-0090c56ab87c" />
<img width="1920" height="1080" alt="Screenshot 2026-10-29 154627" src="https://github.com/user-attachments/assets/18382335-19c4-4cb5-b2f4-45f65b90095d" />
<img width="1920" height="1080" alt="Screenshot 2026-10-29 153517" src="https://github.com/user-attachments/assets/bc651926-ec5e-4d33-9d04-af05b9ddee5f" />
<img width="1920" height="1080" alt="Screenshot 2026-10-29 153508" src="https://github.com/user-attachments/assets/1c75f63f-063c-48dd-8eaa-ad53e6696536" />
<img width="1920" height="1080" alt="Screenshot 2026-10-29 153453" src="https://github.com/user-attachments/assets/44922cdb-efa3-4cb8-b7cd-ca9fc478224d" />
<img width="1920" height="1080" alt="Screenshot 2026-10-29 153316" src="https://github.com/user-attachments/assets/7653d441-7978-41a3-bb3d-f7a04cb97591" />
<img width="1917" height="887" alt="Screenshot 2026-10-29 152551" src="https://github.com/user-attachments/assets/2d61fa6b-de4d-4bdc-b5aa-63c7e3d04358" />
<img width="1920" height="1080" alt="Screenshot 2026-10-29 162832" src="https://github.com/user-attachments/assets/a9a717bf-c576-44c0-93ce-45ee500efa68" />
<img width="1920" height="1080" alt="Screenshot 2026-10-29 162604" src="https://github.com/user-attachments/assets/83211d0d-e5a0-47e6-8047-0f94fd6169ff" />
<img width="1920" height="1080" alt="Screenshot 2026-10-29 161541" src="https://github.com/user-attachments/assets/27e041d7-3fbf-4c84-9cbc-39a30d537ad7" />
<img width="1920" height="1080" alt="Screenshot 2026-10-29 161455" src="https://github.com/user-attachments/assets/1f3c0de5-5064-4f97-ae7d-8ed2a13c1846" />
<img width="1920" height="1080" alt="Screenshot 2026-10-29 161210" src="https://github.com/user-attachments/assets/4ebc6f36-9296-4f76-9ae2-9cce6b309f3d" />



























Result:
Thus, a Simple Storage Service (S3) and EC2 (Elastic Compute Cloud) - instance has been successfully created and launched in AWS
 
