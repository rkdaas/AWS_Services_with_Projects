
## 📘 AWS Solutions Architect SAA-C03 Ultimate Guide 

Preparing for the AWS Solutions Architect Associate (SAA-C03) exam can feel overwhelming. With countless AWS services and extensive documentation to sift through, it's easy to lose focus. This guide aims to streamline your preparation by offering a concise, structured, and exam-oriented approach, ensuring you stay on track and maximize your study efforts.

### Why Use This Guide?

While the official AWS documentation is the most accurate and up-to-date source, it can often feel overwhelming — especially when you're preparing for certification. AWS provides extensive documentation for each service, including:

- **Developer Guides**
- **User Guides**
- **FAQs**
- **API References**
- **Pricing Docs**

But the real question is: **What exactly should you study for the exam?** That's where this guide comes in.

---

### 🎯 The Problem

“Everyone says to study from AWS docs... but no one tells you what to read, what to skip, and how deep to go.”

---

### ✅ How This Guide Helps You

This is a curated, exam-focused study plan for the AWS SAA-C03 exam. Here's how it's different:

| 🔍 **Focus Area**       | **What You Get**                                                                 |
|-------------------------|---------------------------------------------------------------------------------|
| ✔️ **Services by Priority** | Know what to focus on: High / Medium / Low priority based on exam weight         |
| ✔️ **What to Study**        | Bullet-level breakdown of subtopics per service                                |
| ✔️ **What to Skip**         | Avoid wasting time on features not tested in the exam                          |
| ✔️ **Whitepapers**          | Prioritized list of must-read AWS whitepapers with purpose summaries            |
| ✔️ **Hands-On Projects**    | Real-world mini projects to reinforce learning and simulate exam scenarios      |

---

### 🧠 The Smart Strategy

Instead of diving blindly into the AWS docs, this guide provides:

- **Structure**: Follow a clean path from beginner to exam-ready.
- **Clarity**: No second-guessing what to learn.
- **Confidence**: Hands-on + theory + architecture patterns = real understanding.

### 📋 Table of Contents
- [Introduction](#introduction)
- [Why Use This Guide](#why-use-this-guide)
- [Domains](#domains)
    - [Domain 1: Design Resilient Architectures](#domain-1-design-resilient-architectures)
    - [Domain 2: Design High-Performing Architectures](#domain-2-design-high-performing-architectures)
    - [Domain 3: Design Secure Applications and Architectures](#domain-3-design-secure-applications-and-architectures)
    - [Domain 4: Design Cost-Optimized Architectures](#domain-4-design-cost-optimized-architectures)
    - [Domain 5: Define Operationally Excellent Architectures](#domain-5-define-operationally-excellent-architectures)
- [Must-Read AWS Whitepapers](#must-read-aws-whitepapers)
- [Hands-On Projects](#hands-on-projects)

## Domains

### Domain 1: Design Resilient Architectures

#### Amazon EC2 — Priority: High
- [Overview](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/concepts.html)
- [EC2 Instance Types](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/instance-types.html)
- [EC2 Pricing Models](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ec2-instance-purchasing-options.html)
- [EBS Volumes](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ebs-volumes.html)
- [EBS Snapshots](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/EBSSnapshots.html)
- [Auto Recovery](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ec2-instance-recover.html)
- [EC2 Status Checks](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/monitoring-system-instance-status-check.html)
- [EC2 Placement Groups](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/placement-groups.html)
- [Elastic IPs](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/elastic-ip-addresses-eip.html)
- [Instance Metadata (IMDSv2)](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/configuring-instance-metadata-service.html)

#### Elastic Load Balancing — Priority: High
- [Overview](https://docs.aws.amazon.com/elasticloadbalancing/latest/userguide/what-is-load-balancing.html)
- [Types of Load Balancers](https://docs.aws.amazon.com/elasticloadbalancing/latest/userguide/what-is-load-balancing.html)
- [Application Load Balancer](https://docs.aws.amazon.com/elasticloadbalancing/latest/application/introduction.html)
- [Network Load Balancer](https://docs.aws.amazon.com/elasticloadbalancing/latest/network/introduction.html)
- [Classic Load Balancer](https://docs.aws.amazon.com/elasticloadbalancing/latest/classic/introduction.html)
- [Health Checks](https://docs.aws.amazon.com/elasticloadbalancing/latest/application/target-group-health-checks.html)
- [Listener Rules](https://docs.aws.amazon.com/elasticloadbalancing/latest/application/load-balancer-listeners.html)
- [Target Groups](https://docs.aws.amazon.com/elasticloadbalancing/latest/application/load-balancer-target-groups.html)
- [Cross-zone Load Balancing](https://docs.aws.amazon.com/elasticloadbalancing/latest/userguide/how-elastic-load-balancing-works.html#cross-zone-load-balancing)
- [Sticky Sessions](https://docs.aws.amazon.com/elasticloadbalancing/latest/application/sticky-sessions.html)
- [SSL/TLS Termination](https://docs.aws.amazon.com/elasticloadbalancing/latest/application/create-https-listener.html)

#### Amazon S3 — Priority: High
- [Overview](https://docs.aws.amazon.com/AmazonS3/latest/userguide/Welcome.html)
- [Storage Classes](https://docs.aws.amazon.com/AmazonS3/latest/userguide/storage-class-intro.html)
- [Versioning](https://docs.aws.amazon.com/AmazonS3/latest/userguide/Versioning.html)
- [MFA Delete](https://docs.aws.amazon.com/AmazonS3/latest/userguide/MultiFactorAuthenticationDelete.html)
- [Lifecycle Rules](https://docs.aws.amazon.com/AmazonS3/latest/userguide/object-lifecycle-mgmt.html)
- [Cross-Region Replication](https://docs.aws.amazon.com/AmazonS3/latest/userguide/replication.html)
- [S3 Object Lock](https://docs.aws.amazon.com/AmazonS3/latest/userguide/object-lock.html)
- [S3 Durability & Availability](https://docs.aws.amazon.com/AmazonS3/latest/userguide/DataDurability.html)
- [S3 Transfer Acceleration](https://docs.aws.amazon.com/AmazonS3/latest/userguide/transfer-acceleration.html)

#### Amazon S3 Storage Classes
- [Storage classes overview](https://docs.aws.amazon.com/AmazonS3/latest/userguide/storage-class-intro.html)
- [Intelligent-Tiering](https://docs.aws.amazon.com/AmazonS3/latest/userguide/intelligent-tiering.html)
- [Standard-IA & One Zone-IA](https://docs.aws.amazon.com/AmazonS3/latest/userguide/storage-class-intro.html#sc-infrequent-access)
- [Glacier](https://docs.aws.amazon.com/AmazonS3/latest/userguide/storage-class-intro.html#sc-glacier)
- [Glacier Deep Archive](https://docs.aws.amazon.com/AmazonS3/latest/userguide/storage-class-intro.html#sc-glacier-deep-archive)
- [Lifecycle policies](https://docs.aws.amazon.com/AmazonS3/latest/userguide/lifecycle-transition-general-considerations.html)
- [Object tagging](https://docs.aws.amazon.com/AmazonS3/latest/userguide/object-tagging.html)

#### S3 Bucket Policies & Encryption — Priority: High
- [Bucket Policies](https://docs.aws.amazon.com/AmazonS3/latest/userguide/using-iam-policies.html)
- [IAM Policies](https://docs.aws.amazon.com/AmazonS3/latest/userguide/access-policy-language-overview.html)
- [ACLs](https://docs.aws.amazon.com/AmazonS3/latest/userguide/acl-overview.html)
- [Ownership Controls](https://docs.aws.amazon.com/AmazonS3/latest/userguide/about-object-ownership.html)
- [Block Public Access](https://docs.aws.amazon.com/AmazonS3/latest/userguide/access-control-block-public-access.html)
- [Server-Side Encryption (SSE-S3)](https://docs.aws.amazon.com/AmazonS3/latest/userguide/UsingServerSideEncryption.html)
- [SSE-KMS](https://docs.aws.amazon.com/AmazonS3/latest/userguide/UsingKMSEncryption.html)
- [SSE-C](https://docs.aws.amazon.com/AmazonS3/latest/userguide/ServerSideEncryptionCustomerKeys.html)
- [Access Logs](https://docs.aws.amazon.com/AmazonS3/latest/userguide/ServerLogs.html)

#### Amazon Route 53 — Priority: Medium
- [overview](https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/Welcome.html)
- [Routing Policies](https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/routing-policy.html)
- [Simple Routing](https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/routing-policy-simple.html)
- [Weighted Routing](https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/routing-policy-weighted.html)
- [Latency Routing](https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/routing-policy-latency.html)
- [Failover Routing](https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/routing-policy-failover.html)
- [Geolocation Routing](https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/routing-policy-geo.html)
- [Multi-Value Answer](https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/routing-policy-multivalue.html)
- [Health Checks](https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/dns-failover.html)
- [Alias vs Non-Alias Records](https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/resource-record-sets-choosing-alias-non-alias.html)
- [Private Hosted Zones](https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/hosted-zones-private.html)

#### Auto Scaling — Priority: High
- [overview](https://docs.aws.amazon.com/autoscaling/ec2/userguide/what-is-amazon-ec2-auto-scaling.html)
- [Launch Configurations](https://docs.aws.amazon.com/autoscaling/ec2/userguide/LaunchConfiguration.html)
- [Launch Templates](https://docs.aws.amazon.com/autoscaling/ec2/userguide/launch-templates.html)
- [Dynamic Scaling](https://docs.aws.amazon.com/autoscaling/ec2/userguide/as-scale-based-on-demand.html)
- [Predictive Scaling](https://docs.aws.amazon.com/autoscaling/ec2/userguide/ec2-auto-scaling-predictive-scaling.html)
- [Lifecycle Hooks](https://docs.aws.amazon.com/autoscaling/ec2/userguide/lifecycle-hooks.html)
- [Termination Policies](https://docs.aws.amazon.com/autoscaling/ec2/userguide/as-instance-termination.html)
- [Scheduled Scaling](https://docs.aws.amazon.com/autoscaling/ec2/userguide/schedule_time.html)

#### Amazon CloudFront — Priority: Medium
- [Overview](https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/Introduction.html)
- [Edge Locations](https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/Introduction.html)
- [Caching Behavior](https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/ConfiguringCaching.html)
- [TTL Settings](https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/Expiration.html)
- [Signed URLs](https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/private-content-signed-urls.html)
- [Signed Cookies](https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/private-content-signed-cookies.html)
- [Origin Access Control (OAC)](https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/working-with-oac.html)
- [Origin Access Identity (OAI)](https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/private-content-restricting-access-to-s3.html)
- [Error Responses](https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/GeneratingCustomErrorResponses.html)
- [Cache Invalidation](https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/Invalidation.html)
- [Lambda@Edge](https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/lambda-at-the-edge.html)

#### AWS Global Accelerator — Priority: Low
- [Overview & Architecture](https://docs.aws.amazon.com/global-accelerator/latest/dg/what-is-global-accelerator.html)
- [Static IP Addresses](https://docs.aws.amazon.com/global-accelerator/latest/dg/about-accelerators.html#about-accelerators.ip-addresses)
- [Health Checks](https://docs.aws.amazon.com/global-accelerator/latest/dg/introduction-how-it-works-preserving-client-endpoints.html)
- [Endpoint Groups](https://docs.aws.amazon.com/global-accelerator/latest/dg/about-endpoint-groups.html)
- [Difference from CloudFront](https://docs.aws.amazon.com/global-accelerator/latest/dg/introduction-aws-global-accelerator-vs-cloudfront.html)

#### Amazon EFS — Priority: Medium
- [Overview](https://docs.aws.amazon.com/efs/latest/ug/whatisefs.html)
- [When to Use EFS vs EBS vs FSx](https://docs.aws.amazon.com/efs/latest/ug/storage-classes.html)
- [Performance Modes](https://docs.aws.amazon.com/efs/latest/ug/performance.html#performancemodes)
- [Throughput Modes](https://docs.aws.amazon.com/efs/latest/ug/performance.html#throughput-modes)
- [EFS Access Points](https://docs.aws.amazon.com/efs/latest/ug/efs-access-points.html)
- [IAM Authorization](https://docs.aws.amazon.com/efs/latest/ug/auth-and-access-control.html)
- [Lifecycle Management](https://docs.aws.amazon.com/efs/latest/ug/lifecycle-management-efs.html)

#### AWS Transit Gateway — Priority: High
- [Transit Gateway Overview](https://docs.aws.amazon.com/vpc/latest/tgw/what-is-transit-gateway.html)
- [Route Tables](https://docs.aws.amazon.com/vpc/latest/tgw/tgw-route-tables.html)
- [Attachments](https://docs.aws.amazon.com/vpc/latest/tgw/tgw-vpc-attachments.html)
- [Multicast](https://docs.aws.amazon.com/vpc/latest/tgw/tgw-multicast-overview.html)
- [Transit Gateway Flow Logs](https://docs.aws.amazon.com/vpc/latest/tgw/tgw-flow-logs.html)

#### AWS Direct Connect — Priority: Medium
- [Overview](https://docs.aws.amazon.com/directconnect/latest/UserGuide/Welcome.html)
- [Connection Types](https://docs.aws.amazon.com/directconnect/latest/UserGuide/WorkingWithConnections.html)
- [Virtual Interfaces](https://docs.aws.amazon.com/directconnect/latest/UserGuide/WorkingWithVirtualInterfaces.html)
- [Direct Connect Gateway](https://docs.aws.amazon.com/directconnect/latest/UserGuide/direct-connect-gateways.html)
- [Resilient Connections](https://docs.aws.amazon.com/directconnect/latest/UserGuide/resilency_toolkit.html)
- [Integration with Transit Gateway](https://docs.aws.amazon.com/directconnect/latest/UserGuide/direct-connect-transit-gateways.html)

#### Storage Gateway — Priority: Medium
- [File Gateway](https://docs.aws.amazon.com/storagegateway/latest/userguide/StorageGatewayConcepts.html#file-gateway-concepts)
- [Volume Gateway](https://docs.aws.amazon.com/storagegateway/latest/userguide/StorageGatewayConcepts.html#volume-gateway-concepts)
- [Tape Gateway](https://docs.aws.amazon.com/storagegateway/latest/userguide/StorageGatewayConcepts.html#tape-gateway-concepts)
- [Cached vs Stored Volumes](https://docs.aws.amazon.com/storagegateway/latest/userguide/StorageGatewayConcepts.html#volume-gateway-concepts)

#### FSx Services — Priority: Medium
- [FSx for Windows](https://docs.aws.amazon.com/fsx/latest/WindowsGuide/what-is.html)
- [FSx for Lustre](https://docs.aws.amazon.com/fsx/latest/LustreGuide/what-is.html)
- [FSx for NetApp ONTAP](https://docs.aws.amazon.com/fsx/latest/ONTAPGuide/what-is-fsx-ontap.html)
- [FSx for OpenZFS](https://docs.aws.amazon.com/fsx/latest/OpenZFSGuide/what-is-fsx.html)
- [FSx Performance Comparison](https://docs.aws.amazon.com/fsx/latest/WindowsGuide/performance.html)

### Domain 2: Design High-Performing Architectures

#### Amazon RDS — Priority: High
- [overview](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/Welcome.html)
- [DB Engine Options](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/Concepts.DBInstanceClass.html)
- [Multi-AZ Deployments](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/Concepts.MultiAZ.html)
- [Read Replicas](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/USER_ReadRepl.html)
- [Automated Backups](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/USER_WorkingWithAutomatedBackups.html)
- [Manual Snapshots](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/USER_CreateSnapshot.html)
- [Storage Types](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/CHAP_Storage.html)
- [Enhanced Monitoring](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/USER_Monitoring.OS.html)
- [Performance Insights](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/USER_PerfInsights.html)
- [Failover Behavior](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/Concepts.MultiAZ.html#Concepts.MultiAZ.Failover)
- [IAM Authentication](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/UsingWithRDS.IAMDBAuth.html)

#### Amazon Aurora — Priority: High
- [overview](https://docs.aws.amazon.com/AmazonRDS/latest/AuroraUserGuide/CHAP_AuroraOverview.html)
- [Manage Aurora DB cluster ](https://docs.aws.amazon.com/AmazonRDS/latest/AuroraUserGuide/CHAP_Aurora.html)
- [Aurora MySQL](https://docs.aws.amazon.com/AmazonRDS/latest/AuroraUserGuide/Aurora.AuroraMySQL.html)
- [Aurora PostgreSQL](https://docs.aws.amazon.com/AmazonRDS/latest/AuroraUserGuide/Aurora.AuroraPostgreSQL.html)
- [Aurora Serverless v2](https://docs.aws.amazon.com/AmazonRDS/latest/AuroraUserGuide/aurora-serverless-v2.html)
- [Aurora Backtrack](https://docs.aws.amazon.com/AmazonRDS/latest/AuroraUserGuide/AuroraMySQL.Managing.Backtrack.html)
- [Aurora Global Database](https://docs.aws.amazon.com/AmazonRDS/latest/AuroraUserGuide/aurora-global-database.html)
- [Reader Endpoints](https://docs.aws.amazon.com/AmazonRDS/latest/AuroraUserGuide/Aurora.Overview.Endpoints.html)

#### Amazon DynamoDB — Priority: High
- [overview](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/Introduction.html)
- [Primary Key](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/HowItWorks.CoreComponents.html#HowItWorks.CoreComponents.PrimaryKey)
- [Secondary Indexes](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/SecondaryIndexes.html)
- [Global Secondary Index](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/GSI.html)
- [Local Secondary Index](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/LSI.html)
- [On-Demand vs Provisioned](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/HowItWorks.ReadWriteCapacityMode.html)
- [Auto Scaling](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/AutoScaling.html)
- [DynamoDB Accelerator (DAX)](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/DAX.html)
- [DynamoDB Streams](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/Streams.html)
- [TTL](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/TTL.html)
- [Backup & Restore](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/BackupRestore.html)

#### Amazon ElastiCache — Priority: Medium
- [overview](https://docs.aws.amazon.com/AmazonElastiCache/latest/dg/WhatIs.html)
- [Redis vs Memcached](https://docs.aws.amazon.com/AmazonElastiCache/latest/red-ug/SelectEngine.html)
- [Use Cases](https://docs.aws.amazon.com/AmazonElastiCache/latest/red-ug/elasticache-use-cases.html)
- [Replication Groups](https://docs.aws.amazon.com/AmazonElastiCache/latest/red-ug/Replication.html)
- [Automatic Failover](https://docs.aws.amazon.com/AmazonElastiCache/latest/red-ug/AutoFailover.html)
- [Cluster Mode](https://docs.aws.amazon.com/AmazonElastiCache/latest/red-ug/cluster-mode-enabled.html)
- [Data Persistence](https://docs.aws.amazon.com/AmazonElastiCache/latest/red-ug/RedisAOF.html)
- [Eviction Policies](https://docs.aws.amazon.com/AmazonElastiCache/latest/red-ug/Configurations-MemoryDB.html)

#### Amazon SQS & SNS — Priority: High
- [SQS Overview](https://docs.aws.amazon.com/AWSSimpleQueueService/latest/SQSDeveloperGuide/welcome.html)
- [SQS Queue Types](https://docs.aws.amazon.com/AWSSimpleQueueService/latest/SQSDeveloperGuide/sqs-queue-types.html)
- [Message Retention](https://docs.aws.amazon.com/AWSSimpleQueueService/latest/SQSDeveloperGuide/sqs-message-management.html)
- [Delay Queues](https://docs.aws.amazon.com/AWSSimpleQueueService/latest/SQSDeveloperGuide/sqs-delay-queues.html)
- [Visibility Timeout](https://docs.aws.amazon.com/AWSSimpleQueueService/latest/SQSDeveloperGuide/sqs-visibility-timeout.html)
- [Dead-Letter Queues](https://docs.aws.amazon.com/AWSSimpleQueueService/latest/SQSDeveloperGuide/sqs-dead-letter-queues.html)
- [overview](https://docs.aws.amazon.com/sns/latest/dg/welcome.html)
- [SNS Topics](https://docs.aws.amazon.com/sns/latest/dg/sns-create-topic.html)
- [SNS Subscriptions](https://docs.aws.amazon.com/sns/latest/dg/sns-create-subscribe-endpoint-to-topic.html)
- [Fan-out Pattern](https://docs.aws.amazon.com/sns/latest/dg/sns-common-scenarios.html)
- [Encryption](https://docs.aws.amazon.com/sns/latest/dg/sns-server-side-encryption.html)
- [Access Control](https://docs.aws.amazon.com/sns/latest/dg/sns-authentication-and-access-control.html)

#### AWS Lambda — Priority: High
- [Overview](https://docs.aws.amazon.com/lambda/latest/dg/welcome.html)
- [Event Sources](https://docs.aws.amazon.com/lambda/latest/dg/invocation-eventsourcemapping.html)
- [Execution Environment](https://docs.aws.amazon.com/lambda/latest/dg/lambda-runtime-environment.html)
- [IAM Execution Role](https://docs.aws.amazon.com/lambda/latest/dg/lambda-intro-execution-role.html)
- [Cold Starts](https://docs.aws.amazon.com/lambda/latest/dg/lambda-concurrency.html)
- [Timeout & Memory](https://docs.aws.amazon.com/lambda/latest/dg/configuration-function-common.html)
- [Concurrency](https://docs.aws.amazon.com/lambda/latest/dg/configuration-concurrency.html)
- [Versions & Aliases](https://docs.aws.amazon.com/lambda/latest/dg/configuration-versions.html)
- [CloudWatch Integration](https://docs.aws.amazon.com/lambda/latest/dg/monitoring-functions.html)

#### Amazon API Gateway — Priority: High
- [Overview](https://docs.aws.amazon.com/apigateway/latest/developerguide/welcome.html)
- [REST APIs](https://docs.aws.amazon.com/apigateway/latest/developerguide/apigateway-rest-api.html)
- [HTTP APIs](https://docs.aws.amazon.com/apigateway/latest/developerguide/http-api.html)
- [Integration Types](https://docs.aws.amazon.com/apigateway/latest/developerguide/api-gateway-api-integration-types.html)
- [Throttling](https://docs.aws.amazon.com/apigateway/latest/developerguide/api-gateway-request-throttling.html)
- [IAM Authorization](https://docs.aws.amazon.com/apigateway/latest/developerguide/permissions.html)
- [Lambda Authorizer](https://docs.aws.amazon.com/apigateway/latest/developerguide/apigateway-use-lambda-authorizer.html)
- [Cognito Authorizer](https://docs.aws.amazon.com/apigateway/latest/developerguide/apigateway-integrate-with-cognito.html)
- [Stages & Variables](https://docs.aws.amazon.com/apigateway/latest/developerguide/stage-variables.html)
- [Deployment Process](https://docs.aws.amazon.com/apigateway/latest/developerguide/set-up-deployments.html)

#### Amazon CloudWatch — Priority: Medium
- [Overview](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/WhatIsCloudWatch.html)
- [Built-in Metrics](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/aws-services-cloudwatch-metrics.html)
- [Custom Metrics](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/publishingMetrics.html)
- [CloudWatch Alarms](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/AlarmThatSendsEmail.html)
- [Composite Alarms](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/Create_Composite_Alarm.html)
- [CloudWatch Logs](https://docs.aws.amazon.com/AmazonCloudWatch/latest/logs/WhatIsCloudWatchLogs.html)
- [Logs Insights](https://docs.aws.amazon.com/AmazonCloudWatch/latest/logs/AnalyzingLogData.html)
- [Dashboards](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/CloudWatch_Dashboards.html)
- [Metric Filters](https://docs.aws.amazon.com/AmazonCloudWatch/latest/logs/MonitoringLogData.html)

#### Amazon ECS — Priority: Medium
- [Overview](https://docs.aws.amazon.com/AmazonECS/latest/developerguide/what-is-ecs.html)
- [Launch Types](https://docs.aws.amazon.com/AmazonECS/latest/developerguide/launch_types.html)
- [Task Definitions](https://docs.aws.amazon.com/AmazonECS/latest/developerguide/task_definitions.html)
- [Service Configuration](https://docs.aws.amazon.com/AmazonECS/latest/developerguide/service_definition_parameters.html)
- [Networking Modes](https://docs.aws.amazon.com/AmazonECS/latest/developerguide/task-networking.html)
- [Cluster Auto Scaling](https://docs.aws.amazon.com/AmazonECS/latest/developerguide/cluster-auto-scaling.html)
- [Service Discovery](https://docs.aws.amazon.com/AmazonECS/latest/developerguide/service-discovery.html)
- [IAM Roles for Tasks](https://docs.aws.amazon.com/AmazonECS/latest/developerguide/task-iam-roles.html)
- [ALB Integration](https://docs.aws.amazon.com/AmazonECS/latest/developerguide/service-load-balancing.html)
- [CloudWatch Integration](https://docs.aws.amazon.com/AmazonECS/latest/developerguide/cloudwatch-metrics.html)

#### Amazon Redshift — Priority: Medium
- [Overview](https://docs.aws.amazon.com/redshift/latest/mgmt/welcome.html)
- [Data Warehousing Concepts](https://docs.aws.amazon.com/redshift/latest/dg/c_columnar_storage_disk_mem_mgmnt.html)
- [Cluster Architecture](https://docs.aws.amazon.com/redshift/latest/dg/c_high_level_system_architecture.html)
- [Columnar Storage](https://docs.aws.amazon.com/redshift/latest/dg/c_columnar_storage_disk_mem_mgmnt.html)
- [Redshift Spectrum](https://docs.aws.amazon.com/redshift/latest/dg/c-using-spectrum.html)
- [Concurrency Scaling](https://docs.aws.amazon.com/redshift/latest/dg/concurrency-scaling.html)
- [Workload Management](https://docs.aws.amazon.com/redshift/latest/dg/cm-c-defining-query-queues.html)

#### Amazon Athena — Priority: Medium
- [Overview](https://docs.aws.amazon.com/athena/latest/ug/what-is.html)
- [S3 Queries](https://docs.aws.amazon.com/athena/latest/ug/querying-s3-data.html)
- [Data Formats](https://docs.aws.amazon.com/athena/latest/ug/supported-serdes.html)
- [Partitioning](https://docs.aws.amazon.com/athena/latest/ug/partitions.html)
- [Federated Queries](https://docs.aws.amazon.com/athena/latest/ug/connect-to-a-data-source.html)
- [Glue Data Catalog](https://docs.aws.amazon.com/athena/latest/ug/glue-athena.html)

#### AWS Step Functions — Priority: Medium
- [Overview](https://docs.aws.amazon.com/step-functions/latest/dg/welcome.html)
- [State Machines](https://docs.aws.amazon.com/step-functions/latest/dg/concepts-state-machine-structure.html)
- [State Types](https://docs.aws.amazon.com/step-functions/latest/dg/concepts-states.html)
- [Workflow Patterns](https://docs.aws.amazon.com/step-functions/latest/dg/amazon-states-language-state-machine-structure.html)
- [Standard vs Express](https://docs.aws.amazon.com/step-functions/latest/dg/concepts-standard-vs-express.html)
- [Service Integrations](https://docs.aws.amazon.com/step-functions/latest/dg/concepts-service-integrations.html)

---

### Domain 3: Design Secure Applications and Architectures

#### AWS IAM — Priority: High
- [Overview](https://docs.aws.amazon.com/IAM/latest/UserGuide/introduction.html)
- [IAM Entities](https://docs.aws.amazon.com/IAM/latest/UserGuide/id.html)
- [IAM Users](https://docs.aws.amazon.com/IAM/latest/UserGuide/id_users.html)
- [IAM Groups](https://docs.aws.amazon.com/IAM/latest/UserGuide/id_groups.html)
- [IAM Roles](https://docs.aws.amazon.com/IAM/latest/UserGuide/id_roles.html)
- [IAM Policies](https://docs.aws.amazon.com/IAM/latest/UserGuide/access_policies.html)
- [Managed vs Inline Policies](https://docs.aws.amazon.com/IAM/latest/UserGuide/access_policies_managed-vs-inline.html)
- [AssumeRole](https://docs.aws.amazon.com/IAM/latest/UserGuide/id_roles_use_switch-role-api.html)
- [Policy Evaluation Logic](https://docs.aws.amazon.com/IAM/latest/UserGuide/reference_policies_evaluation-logic.html)
- [Permissions Boundaries](https://docs.aws.amazon.com/IAM/latest/UserGuide/access_policies_boundaries.html)
- [MFA](https://docs.aws.amazon.com/IAM/latest/UserGuide/id_credentials_mfa.html)
- [IAM Best Practices](https://docs.aws.amazon.com/IAM/latest/UserGuide/best-practices.html)
- [IAM Access Analyzer](https://docs.aws.amazon.com/IAM/latest/UserGuide/what-is-access-analyzer.html)

#### Amazon Cognito — Priority: Medium
- [Overview](https://docs.aws.amazon.com/cognito/latest/developerguide/what-is-amazon-cognito.html)
- [User Pools](https://docs.aws.amazon.com/cognito/latest/developerguide/cognito-user-identity-pools.html)
- [Identity Pools](https://docs.aws.amazon.com/cognito/latest/developerguide/cognito-identity.html)
- [Federated Identities](https://docs.aws.amazon.com/cognito/latest/developerguide/cognito-identity.html)
- [User Authentication](https://docs.aws.amazon.com/cognito/latest/developerguide/cognito-user-pools-app-integration.html)
- [MFA](https://docs.aws.amazon.com/cognito/latest/developerguide/user-pool-settings-mfa.html)
- [Password Policies](https://docs.aws.amazon.com/cognito/latest/developerguide/user-pool-settings-policies.html)
- [API Gateway Integration](https://docs.aws.amazon.com/apigateway/latest/developerguide/apigateway-integrate-with-cognito.html)

#### AWS KMS & Secrets Manager

##### AWS KMS
- [Overview](https://docs.aws.amazon.com/kms/latest/developerguide/overview.html)
- [CMK Types](https://docs.aws.amazon.com/kms/latest/developerguide/concepts.html#key-types)
- [Key Rotation](https://docs.aws.amazon.com/kms/latest/developerguide/rotate-keys.html)
- [Envelope Encryption](https://docs.aws.amazon.com/kms/latest/developerguide/concepts.html#enveloping)
- [KMS Key Policies](https://docs.aws.amazon.com/kms/latest/developerguide/key-policies.html)
- Integration with AWS Services:
    - [S3](https://docs.aws.amazon.com/AmazonS3/latest/userguide/UsingKMSEncryption.html)
    - [EBS](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/EBSEncryption.html)
    - [Lambda](https://docs.aws.amazon.com/lambda/latest/dg/security-dataprotection.html#security-privacy-atrest)
    - [RDS](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/Overview.Encryption.html)

##### AWS Secrets Manager
- [Overview](https://docs.aws.amazon.com/secretsmanager/latest/userguide/intro.html)
- [Automatic Secret Rotation](https://docs.aws.amazon.com/secretsmanager/latest/userguide/rotating-secrets.html)
- [Versioning](https://docs.aws.amazon.com/secretsmanager/latest/userguide/getting-started.html#rotation-steps)
- [Access Policies](https://docs.aws.amazon.com/secretsmanager/latest/userguide/auth-and-access.html)
- [Secrets Manager vs Parameter Store](https://docs.aws.amazon.com/secretsmanager/latest/userguide/seamless-integration.html#integration-parameters)

#### Amazon VPC
- [Overview](https://docs.aws.amazon.com/vpc/latest/userguide/what-is-amazon-vpc.html)
- [Public vs Private Subnets](https://docs.aws.amazon.com/vpc/latest/userguide/VPC_Subnets.html#subnet-types)
- [Internet Gateway](https://docs.aws.amazon.com/vpc/latest/userguide/VPC_Internet_Gateway.html)
- [NAT Gateway](https://docs.aws.amazon.com/vpc/latest/userguide/vpc-nat-gateway.html)
- [NAT Instance](https://docs.aws.amazon.com/vpc/latest/userguide/VPC_NAT_Instance.html)
- [VPC Peering](https://docs.aws.amazon.com/vpc/latest/peering/what-is-vpc-peering.html)
- [PrivateLink (VPC Endpoints)](https://docs.aws.amazon.com/vpc/latest/privatelink/vpc-endpoints.html)
- [Route Tables](https://docs.aws.amazon.com/vpc/latest/userguide/VPC_Route_Tables.html)
- [Flow Logs](https://docs.aws.amazon.com/vpc/latest/userguide/flow-logs.html)
- [DNS Resolution](https://docs.aws.amazon.com/vpc/latest/userguide/vpc-dns.html)
- [DHCP Options Sets](https://docs.aws.amazon.com/vpc/latest/userguide/VPC_DHCP_Options.html)
- [VPC Endpoint Types](https://docs.aws.amazon.com/vpc/latest/privatelink/vpc-endpoints.html#vpc-endpoint-types)

#### Security Groups & NACLs
- [Security Groups Overview](https://docs.aws.amazon.com/vpc/latest/userguide/VPC_SecuriyGroups.html)
- [NACLs Overview](https://docs.aws.amazon.com/vpc/latest/userguide/vpc-network-acls.html)
- [Security Groups vs NACLs](https://docs.aws.amazon.com/vpc/latest/userguide/VPC_Security.html#VPC_Security_Comparison)
- [Rule Ordering in NACLs](https://docs.aws.amazon.com/vpc/latest/userguide/vpc-network-acls.html#nacl-rules)
- [VPC Flow Logs](https://docs.aws.amazon.com/vpc/latest/userguide/flow-logs.html)

#### AWS Shield & WAF
- [Overview](https://docs.aws.amazon.com/waf/latest/developerguide/what-is-aws-waf.html)
- [Shield Standard vs Advanced](https://docs.aws.amazon.com/waf/latest/developerguide/shield-chapter.html)
- [AWS WAF Web ACLs](https://docs.aws.amazon.com/waf/latest/developerguide/web-acl.html)
- [Rule Types](https://docs.aws.amazon.com/waf/latest/developerguide/waf-rule-statements-list.html)
- [Rate-Based Rules](https://docs.aws.amazon.com/waf/latest/developerguide/waf-rule-statement-type-rate-based.html)
- [DDoS Mitigation](https://docs.aws.amazon.com/waf/latest/developerguide/ddos-overview.html)
- [WAF Integration](https://docs.aws.amazon.com/waf/latest/developerguide/waf-chapter.html#operating-waf)

### Domain 4: Design Cost-Optimized Architectures

#### AWS Cost Explorer
- [Overview](https://docs.aws.amazon.com/cost-management/latest/userguide/ce-what-is.html)
- [Cost breakdown](https://docs.aws.amazon.com/cost-management/latest/userguide/ce-exploring-data.html)
- [Forecasting](https://docs.aws.amazon.com/cost-management/latest/userguide/ce-forecast.html)
- [Filtering](https://docs.aws.amazon.com/cost-management/latest/userguide/ce-filtering.html)
- [RI recommendations](https://docs.aws.amazon.com/cost-management/latest/userguide/ri-recommendations.html)
- [AWS Budgets integration](https://docs.aws.amazon.com/cost-management/latest/userguide/budgets-managing-costs.html)

#### AWS Budgets
- [Budget types](https://docs.aws.amazon.com/cost-management/latest/userguide/budgets-create.html#budget-types)
- [Alerts](https://docs.aws.amazon.com/cost-management/latest/userguide/budgets-sns-policy.html)
- [Account monitoring](https://docs.aws.amazon.com/cost-management/latest/userguide/budgets-managing-costs.html)
- [Tagging](https://docs.aws.amazon.com/cost-management/latest/userguide/budgets-create-filters.html)

#### Spot & Reserved Instances
- [Spot Instances](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/using-spot-instances.html)
- [Spot interruption behavior](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/spot-interruptions.html)
- [Reserved Instances](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ec2-reserved-instances.html)
- [Standard vs Convertible RIs](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/reserved-instances-types.html)
- [Zonal vs Regional RIs](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/reserved-instances-scope.html)
- [EC2 Savings Plans](https://docs.aws.amazon.com/savingsplans/latest/userguide/what-is-savings-plans.html)

#### Right Sizing & Auto Scaling
- [Trusted Advisor](https://docs.aws.amazon.com/awssupport/latest/user/cost-optimization-checks.html)
- [CloudWatch metrics](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/working_with_metrics.html)
- [EC2 recommendations](https://docs.aws.amazon.com/compute-optimizer/latest/ug/view-ec2-recommendations.html)
- [RDS recommendations](https://docs.aws.amazon.com/compute-optimizer/latest/ug/view-rds-recommendations.html)
- [Auto Scaling strategies](https://docs.aws.amazon.com/autoscaling/ec2/userguide/scaling_plan.html)

#### Savings Plans
- [Overview](https://docs.aws.amazon.com/savingsplans/latest/userguide/what-is-savings-plans.html)
- [Compute Savings Plans](https://docs.aws.amazon.com/savingsplans/latest/userguide/what-is-savings-plans.html#compute-savings-plans)
- [EC2 Instance Savings Plans](https://docs.aws.amazon.com/savingsplans/latest/userguide/what-is-savings-plans.html#ec2-instance-savings-plans)
- [Commitment options](https://docs.aws.amazon.com/savingsplans/latest/userguide/what-is-savings-plans.html#key-concepts)
- [Cross-account application](https://docs.aws.amazon.com/savingsplans/latest/userguide/what-is-savings-plans.html#sp-applying)

### Domain 5: Define Operationally Excellent Architectures

#### AWS CloudFormation
- [Overview](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/Welcome.html)
- [Template syntax](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/template-formats.html)
- [Stack lifecycle](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/cfn-whatis-howdoesitwork.html)
- [Parameters](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/parameters-section-structure.html)
- [Outputs](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/outputs-section-structure.html)
- [Mappings](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/mappings-section-structure.html)
- [Conditions](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/conditions-section-structure.html)
- [Change sets](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-changesets.html)
- [Drift detection](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-stack-drift.html)
- [Nested stacks](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-nested-stacks.html)
- [Stack policies](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/protect-stack-resources.html)

#### AWS CloudTrail
- [Overview](https://docs.aws.amazon.com/awscloudtrail/latest/userguide/cloudtrail-user-guide.html)
- [Management & Data events](https://docs.aws.amazon.com/awscloudtrail/latest/userguide/logging-management-and-data-events-with-cloudtrail.html)
- [Trail types](https://docs.aws.amazon.com/awscloudtrail/latest/userguide/create-trail-organization.html)
- [CloudWatch Logs integration](https://docs.aws.amazon.com/awscloudtrail/latest/userguide/monitor-cloudtrail-log-files-with-cloudwatch-logs.html)
- [Encryption](https://docs.aws.amazon.com/awscloudtrail/latest/userguide/encrypting-cloudtrail-log-files-with-aws-kms.html)
- [Event history](https://docs.aws.amazon.com/awscloudtrail/latest/userguide/view-cloudtrail-events.html)
- [CloudTrail Insights](https://docs.aws.amazon.com/awscloudtrail/latest/userguide/cloudtrail-insights.html)

#### AWS Config
- [Overview](https://docs.aws.amazon.com/config/latest/developerguide/WhatIsConfig.html)
- [Rules](https://docs.aws.amazon.com/config/latest/developerguide/evaluate-config.html)
- [AWS managed rules](https://docs.aws.amazon.com/config/latest/developerguide/managed-rules-by-aws-config.html)
- [Custom rules](https://docs.aws.amazon.com/config/latest/developerguide/evaluate-config_develop-rules.html)
- [Conformance packs](https://docs.aws.amazon.com/config/latest/developerguide/conformance-packs.html)
- [Timeline view](https://docs.aws.amazon.com/config/latest/developerguide/view-manage-resource.html)
- [Remediation actions](https://docs.aws.amazon.com/config/latest/developerguide/remediation.html)
- [Organizations integration](https://docs.aws.amazon.com/config/latest/developerguide/config-rule-multi-account-deployment.html)

#### Amazon CloudWatch
- [Overview](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/WhatIsCloudWatch.html)
- [Composite alarms](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/Create_Composite_Alarm.html)
- [Dashboards](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/CloudWatch_Dashboards.html)
- [Anomaly detection](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/CloudWatch_Anomaly_Detection.html)
- [Log Insights](https://docs.aws.amazon.com/AmazonCloudWatch/latest/logs/AnalyzingLogData.html)
- [Metric math](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/using-metric-math.html)
- [Alarm actions](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/AlarmThatSendsEmail.html)
- [EventBridge integration](https://docs.aws.amazon.com/AmazonCloudWatch/latest/events/WhatIsCloudWatchEvents.html)

#### AWS Trusted Advisor
- [Overview](https://docs.aws.amazon.com/awssupport/latest/user/trusted-advisor.html)
- [Categories](https://docs.aws.amazon.com/awssupport/latest/user/trusted-advisor.html)
- [Check categories](https://docs.aws.amazon.com/awssupport/latest/user/trusted-advisor-categories.html)
- [Support plans](https://docs.aws.amazon.com/awssupport/latest/user/trusted-advisor-check-reference.html)
- [API access](https://docs.aws.amazon.com/awssupport/latest/user/trustedadvisor.html)
- [Organization-wide checks](https://docs.aws.amazon.com/awssupport/latest/user/organizational-view.html)

#### AWS Systems Manager
- [Overview](https://docs.aws.amazon.com/systems-manager/latest/userguide/systems-manager.html)
- [Run Command](https://docs.aws.amazon.com/systems-manager/latest/userguide/execute-remote-commands.html)
- [Patch Manager](https://docs.aws.amazon.com/systems-manager/latest/userguide/systems-manager-patch.html)
- [Session Manager](https://docs.aws.amazon.com/systems-manager/latest/userguide/session-manager.html)
- [Parameter Store](https://docs.aws.amazon.com/systems-manager/latest/userguide/systems-manager-parameter-store.html)
- [Automation Documents](https://docs.aws.amazon.com/systems-manager/latest/userguide/automation-documents.html)
- [State Manager](https://docs.aws.amazon.com/systems-manager/latest/userguide/systems-manager-state.html)
- [OpsCenter](https://docs.aws.amazon.com/systems-manager/latest/userguide/OpsCenter.html)

#### AWS CodeDeploy
- [Overview](https://docs.aws.amazon.com/codedeploy/latest/userguide/welcome.html)
- [Deployment types](https://docs.aws.amazon.com/codedeploy/latest/userguide/deployments.html)
- [In-place deployments](https://docs.aws.amazon.com/codedeploy/latest/userguide/deployments-in-place.html)
- [Blue/Green deployments](https://docs.aws.amazon.com/codedeploy/latest/userguide/deployments-blue-green.html)
- [Service integrations](https://docs.aws.amazon.com/codedeploy/latest/userguide/integrations.html)
- [Lifecycle events](https://docs.aws.amazon.com/codedeploy/latest/userguide/reference-appspec-file-structure-hooks.html)
- [AppSpec file](https://docs.aws.amazon.com/codedeploy/latest/userguide/reference-appspec-file.html)
- [CloudWatch alarms integration](https://docs.aws.amazon.com/codedeploy/latest/userguide/monitoring-cloudwatch-alarms.html)

#### AWS CodePipeline
- [Overview](https://docs.aws.amazon.com/codepipeline/latest/userguide/welcome.html)
- [Pipeline structure](https://docs.aws.amazon.com/codepipeline/latest/userguide/concepts-pipeline-execution.html)
- [Integrations](https://docs.aws.amazon.com/codepipeline/latest/userguide/integrations.html)
- [Manual approvals](https://docs.aws.amazon.com/codepipeline/latest/userguide/approvals.html)
- [Pipeline artifacts](https://docs.aws.amazon.com/codepipeline/latest/userguide/concepts-artifacts.html)

## Must-Read AWS Whitepapers

### AWS Well-Architected Framework
- [Main framework whitepaper](https://docs.aws.amazon.com/wellarchitected/latest/framework/welcome.html)
- **Five Pillars**:
    - [Operational Excellence](https://docs.aws.amazon.com/wellarchitected/latest/operational-excellence-pillar/welcome.html)
    - [Security](https://docs.aws.amazon.com/wellarchitected/latest/security-pillar/welcome.html)
    - [Reliability](https://docs.aws.amazon.com/wellarchitected/latest/reliability-pillar/welcome.html)
    - [Performance Efficiency](https://docs.aws.amazon.com/wellarchitected/latest/performance-efficiency-pillar/welcome.html)
    - [Cost Optimization](https://docs.aws.amazon.com/wellarchitected/latest/cost-optimization-pillar/welcome.html)
- [Well-Architected Tool](https://docs.aws.amazon.com/wellarchitected/latest/userguide/intro.html)

### Shared Responsibility Model
- [Shared Responsibility Model](https://aws.amazon.com/compliance/shared-responsibility-model/)

### How AWS Pricing Works
- [Main pricing whitepaper](https://docs.aws.amazon.com/whitepapers/latest/how-aws-pricing-works/welcome.html)
- [EC2 pricing](https://docs.aws.amazon.com/whitepapers/latest/how-aws-pricing-works/amazon-elastic-compute-cloud-amazon-ec2.html)
- [S3 pricing](https://docs.aws.amazon.com/whitepapers/latest/how-aws-pricing-works/amazon-simple-storage-service-amazon-s3.html)
- [Lambda pricing](https://docs.aws.amazon.com/whitepapers/latest/how-aws-pricing-works/aws-lambda.html)
- [DynamoDB pricing](https://docs.aws.amazon.com/whitepapers/latest/how-aws-pricing-works/amazon-dynamodb.html)
- [RDS pricing](https://docs.aws.amazon.com/whitepapers/latest/how-aws-pricing-works/amazon-relational-database-service-amazon-rds.html)
- [Cost calculator](https://calculator.aws/#/)
- [Cost drivers overview](https://docs.aws.amazon.com/whitepapers/latest/how-aws-pricing-works/key-principles.html)

---

## Upgraded Hands-On Projects for Mastery

### 3-Tier Web App
- **Tags**: Compute + Networking + Storage.
- Deploy EC2 behind ALB, use Auto Scaling.
- RDS backend, security groups per tier.
- Bastion Host for SSH access to private subnet.

### Static Website
- **Tags**: Web Hosting + CDN + DNS.
- S3 bucket for static site.
- CloudFront for distribution.
- Route 53 with alias record.

### Serverless API
- **Tags**: Fully Serverless Stack.
- Lambda CRUD operations.
- API Gateway integration, rate limiting.
- Cognito auth or IAM.

### Secure VPC
- **Tags**: VPC + Security + NAT.
- NAT Gateway for private subnet.
- EC2 in private subnet with Bastion access.
- Security Groups and NACLs.

### Auto Scaling Group
- **Tags**: Elastic Compute Scaling.
- Launch template, scaling policy.
- Attach to ALB Target Group.

### S3 Security
- **Tags**: IAM + Storage Security.
- Use IAM and bucket policy combo.
- Apply SSE-KMS.
- Enable logging.

### Monitoring Setup
- **Tags**: Ops Monitoring.
- Alarms on EC2 metrics.
- Log Group setup.
- Dashboard for visualization.

### IaC Setup
- **Tags**: Infrastructure Automation.
- Parameterized template for 3-tier app.
- Stack update and rollback.
- Nested stacks.

### Messaging Architecture
- **Tags**: Microservice Decoupling.
- SNS to fan-out to SQS.
- Lambda to process messages.
- DLQs and retry logic.

### CI/CD Pipeline
- **Tags**: DevOps Automation.
- CodeCommit → Build → Deploy.
- Blue/Green deployment.
- Approval actions.
