# Ex--3-AWS-Account-setup-and-S3-creation-

### NAME: THIRISHA A

### REG NO: 212223040228

# Introduction:

In this lab, we are going to be introduced to one of the famous Cloud Service providers, Amazon Web Services (AWS). We will work on Amazon Simple Storage Service (S3), which provides storage through web service interfaces (REST, SOAP, and BitTorrent). In S3, the data is stored in the form of buckets. Buckets serve as root folders where we can add, create, or upload files and folders. We can create multiple buckets for different purposes, and each bucket can have different access control policies.

# Objectives:
Create a Bucket in Amazon S3.
Add Objects (files and folders) to the bucket.
Access, move, download, and delete the objects.
Delete the Bucket.

# Illustration:

### Step 1: Choose S3 Service

Choose the S3 service from the list of services provided by AWS.

<img width="887" height="468" alt="379127248-d641bb01-a8f8-405c-914b-5ff7840a539d" src="https://github.com/user-attachments/assets/8c39ab1e-d507-472e-bcf5-09fbaef1e73b" />


### Step 2: Create a Unique Bucket

After selecting the S3 service, click on the "Create Bucket" button on the page. The bucket name must be unique, contain no uppercase letters, and have no special characters. If you enter any of these, an error will display, preventing the bucket from being created.

<img width="887" height="467" alt="379127541-8f0c2e75-1106-4666-b67d-6335aab13ab8" src="https://github.com/user-attachments/assets/8d81e837-5f3f-4257-a326-d449d495a66a" />

<img width="887" height="425" alt="379127408-6a447548-5dbb-4bee-be9a-14823d0bf6b0" src="https://github.com/user-attachments/assets/9229981a-43d2-40fb-a2d5-d7447e44359e" />


<img width="885" height="467" alt="379127714-216498f3-1fbd-457e-b930-9589d28be372" src="https://github.com/user-attachments/assets/eeb7bf5e-df10-4c6b-b64b-da244db4d394" />

<img width="896" height="472" alt="379128918-9ed831a6-3a1c-4aee-90d9-d871af80bd6c" src="https://github.com/user-attachments/assets/fcc28f60-573f-420c-926f-60a6075905b6" />

<img width="992" height="518" alt="379129821-e32fc9f3-c82a-4b72-8b10-7a0477f9ccd6" src="https://github.com/user-attachments/assets/d7692905-fd2c-49be-9326-da20ea33d7a5" />

For region selection, choose a region from the available list. It is recommended to select a region nearby your location for higher availability. In this lab, I selected Sydney, as it is near my country, New Zealand. Remember to provide a unique bucket name with no special characters or uppercase letters.

### Step 3: Upload Files to the Bucket

Now, I have uploaded some files into the bucket I just created. There are no restrictions on uploading file types, but the size of each file must be less than 5 terabytes.

<img width="465" height="402" alt="379130813-3a137296-7bce-474e-9aee-90f1270da0b5" src="https://github.com/user-attachments/assets/ffa324b1-1305-4041-9fe4-d11d6a4f501b" />


<img width="1023" height="520" alt="379130611-b4aa897c-f2e2-4473-8f90-595b530529e9" src="https://github.com/user-attachments/assets/ffaed397-31de-4940-b858-d84ef3aa113f" />

You can upload files of any extension, folders, and subfolders. The images below explain that you can drag and drop files or select them from your computer. After uploading a file, you can download, cut, copy, make it public, rename, or delete it. Making a file public means everyone can access it, and you will receive a link (e.g., https://s3-ap-southeast-2.amazonaws.com/...) to share it.

<img width="746" height="362" alt="379131284-5f1fee62-d590-494f-8345-aeb80745e810" src="https://github.com/user-attachments/assets/5b79c82b-3644-4653-a359-c8f3c8e8fb3c" />


<img width="887" height="416" alt="379131786-b3030041-ce14-43a8-8e6c-4c26a875d52e" src="https://github.com/user-attachments/assets/71769248-127d-40a2-bd9d-9830f261eb31" />

### Step 4: Upload a Folder

You can also upload a folder to the bucket. If your local folder contains subfolders and data, all data inside the parent folder will be uploaded. The images below show how to upload a folder by dragging and dropping or browsing.


<img width="883" height="351" alt="379131961-f0ad8c4e-0d66-490f-a4e0-3ecc1d39ba25" src="https://github.com/user-attachments/assets/7c762eb1-fe6d-4514-ae46-7728c6f37ce5" />

### Step 5: Delete the Bucket

To delete a bucket, you must retype the bucket name. This policy is implemented by Amazon to confirm your action because deleting a bucket can remove large amounts of data.


<img width="350" height="357" alt="379132408-c09b5618-9d48-4d70-b59a-e76dd9c163f6" src="https://github.com/user-attachments/assets/e49f575e-c9ee-4ac9-991c-90f4b7c579ed" />


<img width="866" height="367" alt="379133596-a90ffaae-5bbd-4306-9227-f6f4dd715395" src="https://github.com/user-attachments/assets/796be1be-b092-42cd-b9fd-6846e7db7aa4" />



# RESULT:

Successfully created, managed, and deleted an S3 bucket on AWS, demonstrating the ability to upload, access, and control objects within Amazon S3.









