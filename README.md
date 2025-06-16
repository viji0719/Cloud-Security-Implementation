# Cloud-Security-Implementation

**COMPANY** : CODETECH IT SOLUTIONS

**NAME** : PRAGATHI P

**INTERN ID** : CT04DG1065

**DOMAIN** :Cloud Computing

**DURATION** : 4 WEEKS

**MENTOR** :Neela Santhosh Kumar

**DESCRIPTION:**

In today's rapidly evolving digital landscape, security is a foundational component of every cloud-based infrastructure. As organizations shift more operations to cloud platforms, ensuring the confidentiality, integrity, and availability of data has become a primary concern. This task focuses on implementing cloud security through three key areas: Identity and Access Management (IAM) policies, secure cloud storage configuration, and data encryption. These steps help establish a strong security baseline for any application or system deployed on the cloud.

1. **Implementing IAM Policies**

Identity and Access Management (IAM) is a framework that allows administrators to manage user identities and their permissions within a cloud environment. The primary objective of IAM is to ensure that the right individuals have the right access to resources at the right time.

To begin with, IAM users are created for each individual who needs access to the cloud platform. Users are grouped based on roles, and access permissions are assigned using IAM policies. These policies are written in JSON and define what actions a user or group can perform on specific cloud services.

For example, a policy may grant a user read-only access to a specific storage bucket or full administrative privileges over computing resources. The principle of least privilege is followed strictly—users are granted only the permissions they need to complete their tasks. This minimizes the risk of accidental or malicious changes to cloud resources.

Multi-Factor Authentication (MFA) is also implemented for added security, especially for users with high privileges. By combining something the user knows (password) with something they have (authentication device), MFA significantly reduces the chances of unauthorized access.

2. **Securing Cloud Storage**
   
Cloud storage services, such as Amazon S3 or Azure Blob Storage, provide a reliable way to store and retrieve data over the internet. However, these storage services must be carefully configured to avoid unintentional data exposure.

The first step in securing cloud storage is to ensure that all storage buckets or containers are private by default. Public access to storage must be blocked unless absolutely necessary. For example, if a website needs to serve images from a bucket, then only read-only access to those specific files should be granted—never full write access.

Bucket policies are applied to define who can read, write, or delete objects inside a bucket. Logging and versioning features are enabled to track changes and keep a history of files. Lifecycle rules can also be configured to automatically delete or archive files after a certain period, reducing unnecessary storage usage and improving compliance.

In addition, access logs are enabled to monitor usage patterns and detect unusual activities. These logs are valuable for auditing and responding to incidents quickly.

3. **Data Encryption**

Data encryption ensures that information stored or transmitted on the cloud is unreadable without the correct cryptographic keys. This task includes implementing both server-side encryption and key management.

Cloud platforms offer two types of server-side encryption:

SSE-S3 (Amazon-managed keys): The cloud provider handles the encryption and key management.
SSE-KMS (Customer-managed keys): The user manages the encryption keys using services like AWS Key Management Service (KMS).
Using KMS, a custom encryption key is created and configured to be used with a specific storage bucket. Only authorized users or services can use this key to encrypt and decrypt data, providing tighter control over data access.

Encryption is applied by default for all objects stored in the bucket. Any file uploaded will be automatically encrypted, and only users with key access permissions will be able to download or read it.

**Conclusion**

This task provides a comprehensive approach to securing cloud infrastructure by focusing on three pillars: IAM, secure storage, and encryption. Through IAM policies, organizations can control who accesses what. With proper storage configurations, data exposure risks are minimized. And with encryption, even if data is accessed, it remains unreadable to unauthorized users.

Together, these implementations form a strong foundation for secure cloud operations, meeting both industry best practices and compliance requirements. By applying these measures, organizations can ensure the safety of sensitive information and maintain trust in their cloud systems.

**OUTPUT**
<img width="1440" alt="Image" src="https://github.com/user-attachments/assets/d65aed6b-74ed-43cd-8dd8-0e57772263c1" />

<img width="1440" alt="Image" src="https://github.com/user-attachments/assets/2287ac89-2230-417a-95f5-836eba4db686" />

<img width="1440" alt="Image" src="https://github.com/user-attachments/assets/fb44aa04-2775-46a4-91f6-4acfdaace77d" />

<img width="1438" alt="Image" src="https://github.com/user-attachments/assets/55759186-05c4-4bbd-a143-0b4a05f8e9dc" />

<img width="1440" alt="Image" src="https://github.com/user-attachments/assets/eb9b55c8-fedf-4b4b-b356-7cfb709b9b77" />

<img width="1440" alt="Image" src="https://github.com/user-attachments/assets/b8bb594b-6a99-451f-91ee-121875d89b55" />

<img width="1440" alt="Image" src="https://github.com/user-attachments/assets/26515703-21be-4301-9b3a-beb47102ec10" />

<img width="1440" alt="Image" src="https://github.com/user-attachments/assets/10800339-9ef9-4bf8-a4cb-7977bb7fac53" />

<img width="1439" alt="Image" src="https://github.com/user-attachments/assets/e91b8963-9c31-49b3-9104-73ff9c17fdff" />
