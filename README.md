# Ex-02-Cloud-Storage-creation-S3-and-Launching-an-EC2-Instance-in-AWS

---

## Aim

To create an S3 bucket and EC2 instances for Linux and Windows on AWS.

---

## S3 Bucket

An **Amazon S3 bucket** is a public cloud storage resource available in the AWS Simple Storage Service (S3) platform. It provides **object-based storage**, where data is stored inside S3 buckets in distinct units called **objects** instead of traditional files.

---

## EC2 Instance

An **Amazon EC2 instance** is a virtual server in Amazon's Elastic Compute Cloud (EC2), a scalable compute platform for running applications on AWS. EC2 offers various **instance types** with different configurations of CPU, memory, storage, and networking resources to suit different workloads.

---

## Procedure

### Step 1: Log in to AWS Console

* Access the [AWS Console](https://aws.amazon.com/console).

### Step 2: Create an S3 Bucket

* Navigate to the **S3** service.
* Click on **Create bucket**.
* Enter a **Bucket name** and select a **Region**.
* Configure settings (e.g., versioning, public access).
* Click **Create bucket** to finalize.

### Step 3: Create an EC2 Instance (Linux)

* Go to the **EC2** service.
* Click on **Launch Instance**.
* Select an **Amazon Machine Image (AMI)** for Linux (e.g., Amazon Linux 2).
* Choose an **Instance Type** (e.g., t2.micro for Free Tier).
* Configure **Instance Details**, **Storage**, and **Security Group**.
* Review and **Launch** using an existing or new key pair.

### Step 4: Create an EC2 Instance (Windows)

* Return to the **EC2** service and click **Launch Instance**.
* Select a **Windows AMI** (e.g., Windows Server 2019).
* Choose an **Instance Type**.
* Configure **Instance Details**, **Storage**, and **Security Group**.
* Review and **Launch** with a key pair for future login.

### Step 5: Verify and Connect to Instances

* Check the **status** of both instances in the EC2 Dashboard.
* **Connect to the Linux instance** using **SSH**.
* **Connect to the Windows instance** using **RDP (Remote Desktop Protocol)**.

---

## Output

![AWS EC2 & S3 Screenshot](https://github.com/user-attachments/assets/30224a3b-88e6-462b-b369-585fbf9739e7)

---

## Result

Successfully created an S3 bucket and EC2 instances for both Linux and Windows, demonstrating effective cloud resource management on AWS.

---

