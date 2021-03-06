Again, like most of my other posts this is mostly targeted to debug the myths and hoopla surrounding new buzz words.

I am going to talk today about different cloud services offered by AWS (Amazon Web Services) which is an Amazon Subsidiary that provides services over the cloud.

Let's start with revising one of the most popular statements made about the cloud.

"Cloud is just someone else's computer". 

A lot of people really hate it as this statement in a way undermines the complexity behing the scenes of cloud services, but for me it makes perfect sense. As a new kid in college with little background in Computer Science, I would get quite confused when my professors would mention about Cloud Engineering or about different Cloud Services available. That statement I believe was the first definition which made sense to me and was simple enough to give me a basic understanding of cloud which I can then use to deep dive into the complicacies behind.

Without further ado, let's get right to it.

| ﻿S.No. 	| Service 	| What it really is? 	| In Plain English 	| Comparable service by other cloud vendors 	| Other related services by AWS 	|
|-------	|-----------------------------	|-------------------------------------	|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------	|-------------------------------------------	|-----------------------------------------------------------------	|
| 1 	| EC2 (Elastic Compute Cloud) 	| Virtual servers 	| Virtual servers that you can use to host your services and applications. And pay by the hour. Before we had cloud ecoystems like AWS and Azure you had Linode, DigitalOcean and Rackspace who would also provide you virtual and dedicated servers. 	| Azure Virtual Machines 	| Amazon Lightsail, EC2 Container Service, EC2 Container Registry 	|
| 2 	| Lambda 	| Serverless 	| A service that runs your JS, Python, Java code snippets in response to some event or schedule. No need for you to provision any server for this. Cloud provider takes care of that. That is why serverless. 	| Azure Functions 	|  	|
| 3 	| S3 (Simple Storage Service) 	| Object Storage 	| As the name says, this is a huge server where you can send objects that could be anything and everything. You can use it store your website, web app assets, backups, archiving, etc. A lot of other AWS services have inbuilt capability to read from and write into S3. 	| Azure Storage—Block Blob 	| Elastic Book Store, Elastic File System 	|
| 4 	| Glacier 	| Archiving or Cool Storage 	| Storage to keep your infrequently accessed data for archival purposes only. 	| Azure Storage - Standard Archive 	|  	|
| 5 	| Cloud Virtual Networking 	| Virtual Private Cloud 	| Your own little space for your services in the big bad world of internet. So basically your own isolated, private environment in the cloud. Users have control over their virtual networking environment, including selection of their own IP address range, creation of subnets, and configuration of route tables and network gateways. 	| Azure Virtual Network 	|  	|
| 6 	| Route 53 	| DNS (Domain Name System) Management 	| Service to manage your DNS records as you do let's say at GoDaddy or HostGator. 	| Azure DNS 	|  	|
| 7 	| CloudFront 	| Content Delivery Network 	| Make your websites load faster by spreading out static file delivery to be closer to where your users are. Quite similar to what Akamai or MaxCDN does. 	| Azure CDN 	|  	|
| 8 	| Relational Database 	| RDS 	|  	|  	|  	|
| 9 	| NoSQL Document Storage 	| DynamoDB 	|  	| Cosmos DB 	|  	|
| 10 	| In Memory Caching 	| ElasticCache 	|  	| Azure Redis Cache 	|  	|
| 11 	| Elastic Data Warehouse 	| Redshift 	|  	| SQL Data Warehouse 	|  	|
| 12 	| Big Data Processing 	| Elastic Map Reduce (EMR) 	|  	| HDInsight 	|  	|
| 13 	| Data Orchestration 	| Data Pipeline 	|  	| Data Factory 	|  	|