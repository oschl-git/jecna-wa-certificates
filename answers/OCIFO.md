### Q&A
- Which among the following is not one of the supported DNS records for OCI DNS service? - **NAPTR**

- State whether the following statement is True or False: *Default NS and SOA records are automatically generated when a Zone is created.* - **True**

- Which among the following is the DNS server that takes website name or URL requests from users and checks the records attained obtained from authoritative DNS servers for the associated IP address? - **Recursive DNS**

- Which among the following is not the common use case for DNS Traffic Management? - **Transaction based Steering** 

- Which among the following is not one of the components of the health checks service? - **Child Zone**

- State whether the following statement is True or False: *Conditional steering can be used for zero rating services so that preferred ASNs can be directed to free resources while all other traffic can be directed to paid resources.* - **True**

- Which among the following is not the common use case for OCI WAF? - **Protection against SYN flooding**

- State whether the following statement is True or False: *OCI WAF uses OWASP ModSecurity Core Rule Set (CRS) to protect against the most common web vulnerabilities.* - **False**

- State whether the following statement is True or False: *OCI WAF cannot protect the workloads against a missing function-level access control vulnerability.* - **False**

- Which of the following are is a resource manager job type? - **Stack**

- Which Oracle Cloud Infrastructure (OCI) service can you use to create and manage your infrastructure? - **OCI Resource Manager**

- Which of the following represents the job lifecycle state? - **In progress**

- State whether the following statement is True or False: *OCI streaming service is based on Apache ActiveMQ.* - **False**

- Which of the following represents the maximum duration for which messages are retained in an OCI streaming service? - **7 days**

- Which of the following represents the benefit of streams? - **All of Above**

- The Alarms feature of the Monitoring service works with which OCI services to inform you when metrics meet alarm-specified trigger? - **Notifications**

- The Monitoring service uses which of the following to notify you when metrics qualifies a specified rule threshold? - **Alarms**

- The Monitoring service uses which service to monitor resources? - **Metrics**

- The Events service has a limitation of how many rules per tenancy? - **50**

- Events can only be delivered to certain Oracle Cloud Infrastructure services with a rule. Name these rules. 
	- **Functions**
	- **Streaming**
	- **Notifications**
- State whether the following statement is True or False: *Oracle Cloud Infrastructure Events enables you to create automation based on the state changes of resources throughout your tenancy.* - **True

- What is the maximum execution timeout for Oracle functions? - **120 seconds**

- When starting a container to run Oracle functions, the container runs processes as which user? - **Oracle functions use fn user to run the process inside the container with no added privileges.**

- What is the maximum memory threshold for Oracle functions? - **1024 MB**

- A DevOps engineer wants to push an image to OCIR and that image needs to be tagged appropriately so as to identify the docker registry where image needs to be pushed. Which of the following will be added to image tag? - **Object Storage Namespace**

- Which of the following docker commands is not required for saving an image to OCIR? - **docker save**

- Which of the following is required to login to the OCIR Container Registry? - **Auth Tokens**

- Which of the following is not a method to create a kubernetes cluster? - **OCI SDK**

- Which of the following statements is incorrect about the Oracle Container Engine for kubernetes (OKE)? - **Worker nodes in node pool can be different shapes**

- State whether the following statement is True or False: *Kubernetes cluster worker nodes should be placed in private subnet of the VCN.* - **True**

- You have created a new compartment called production to host some Production apps. You have also created users in Your Tenancy and added them to a group called “Production_Group”. Your Users are still unable to access Production Compartment. How can you resolve this situation? - **Write an IAM Policy for Production Group granting it access to production compartment**

- You have the following compartment structure in your tenancy: Root Compartment->Training->Training-sub1->Training-sub2 You create a policy in the Root compartment to allow the default admin of the account (Administrator) to manage block volumes in compartment Training-sub2. What policy would you write to meet this requirement? - **Allow group Administrator to manage volume-family in compartment Training: Training-sub1: Training-sub2**

- You have an instance running in a development compartment that needs to make API calls against other OCI services, but you do not want to configure user credentials or a store a configuration file on the instance. How can you meet this requirement? - **Create a dynamic group with matching rules to include your instance and write a policy for this dynamic group**

- You can use the OCI Vault service to create and manage which of the following resources? - **Secrets, Vaults, Keys**

- Which of the following are Key Management (OCI Vault) capabilities? Choose all that apply.
	- **Create keys/quickly disable keys (so they can’t be used by anyone)/re-enable disabled keys**
	- **Create highly available key vaults to durably store your encryption keys**
	- **Rotate your keys to meet your security governance and regulatory compliance needs**

- State whether the following statement is True or False: *After a key vault is deleted, it cannot be recovered.* - **True**

- You can Filter Costs by which of the following? Choose all that apply.
	- **Compartment**
	- **Tags**

- OCI Budgets are used to achieve which of the following? Choose the 2 best options.
	- **Set alerts on your budgets at predefined thresholds to get notified**
	- **Track actual and forecasted spending for the entire tenancy or per compartment**

- Using compartment quotas administrators can limit usage of resources per which of the following?
	- **Region**
	- **Tenancy**
	- **Compartment**
	- **Availability Domain**

- Oracle Cloud Infrastructure SLA covers which of the following?
	- **Availability**
	- **Manageability**
	- **Performance**

- State whether the following statement is True or False: *You must have a Valid CSI and Support Account in order to submit a Service Request.* - **True**
- Where will you find your Customer Support Identifier
	- **Welcome Letter**
	- **In your contract document**
	- **Tenancy Details Page in OCI Console**

- Which of the following OCI Components will you use to implement Network Security?
	- **Security Lists**
	- **Virtual Cloud Network** 
	- **Gateways**

- When Customers deploy their workload on Oracle Cloud Infrastructure, they are responsible for which of the following? Choose all that apply.
	- **Key management**
	- **User credentials including strong password, password renewal, secure user access to OCI**
	- **Setting up strong IAM policies**

- Which of the following design principles you will apply to deploy, operate, and use your applications securely in Oracle Cloud Infrastructure? - **All of the above**
