# Virtual-Machine-on-AWS
This lab demonstrates how to provision and configure a virtual machine using Amazon Web Services (AWS) through Amazon EC2. It covers launching an instance, configuring access, and connecting remotely.
## 📎 Project Demo  

[![Watch the demo](https://cdn.loom.com/sessions/thumbnails/99d6412d59224805879e71d128c934a7.jpg)](https://www.loom.com/share/99d6412d59224805879e71d128c934a7)

This video demonstrates the full process of provisioning and connecting to an AWS EC2 Windows instance using RDP.

🛠️ Technologies Used

  AWS Management Console

  Amazon EC2

  RDP (Remote Desktop Protocol)

  Windows Server (AMI-based instance)

🚀 Steps
🔹 Step 1: Log into AWS

  Access the AWS Management Console

  Navigate to EC2 Dashboard

🔹 Step 2: Launch Instance

  Click Launch Instance

  Choose a Windows Server AMI

  Select instance type (e.g., t2.micro)

  ![LAB1SHOT3](https://github.com/user-attachments/assets/8b146b72-abb5-4b85-9d8b-ea26bad34451)


🔹 Step 3: Configure Key Pair

  Create or select an existing key pair

  Download .pem file (used to decrypt the administrator password)

📸 Add screenshot here

🔹 Step 4: Configure Network Settings

  Allow RDP (port 3389)

  Review and launch instance

📸 Add screenshot here

🔹 Step 5: Connect to Instance via RDP

  Retrieve the Windows administrator password using the key pair

  Open Microsoft Remote Desktop

  Enter the public IP address of the instance

  Log in with the administrator credentials

📸 Add screenshot here

🧪 Validation

  Successfully connected to EC2 instance using RDP

  Verified full access to the Windows desktop environment

⚠️ Troubleshooting

  Unable to connect: Ensure port 3389 is open

  Password issues: Confirm correct key pair was used to decrypt password

  RDP not launching: Check Remote Desktop settings on your machine

📊 Key Takeaways

  Learned how to deploy a Windows-based cloud VM

  Gained experience with RDP remote access

  Verified proper deployment by connecting to the instance

  Understood core cloud deployment and access workflows

🎯 Skills Demonstrated

  Cloud Computing (AWS)

  Virtual Machine Deployment

  Remote Desktop (RDP)

  Basic System Administration
