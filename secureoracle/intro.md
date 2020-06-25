# SecureOracle Workshop Overview                                    

The SecureOracle workshop represents a demonstration platform for the **Oracle IAM Suite 12c R2 PS4 (12.2.1.4.0)** which includes the following Oracle components:

* Identity Governance:
	* OIG 12c, SOA Suite 12c, BI Publisher 12c, OUD 12c, DB 19c and 12c Connectors
* Access Management:
	* OAM 12c, OHS/WebGate 12c, OUD 12c and DB 19c
* Development Tools and Assets:
	* [JDeveloper 12c with SOA Extensions](http://www.oracle.com/technetwork/middleware/soasuite/downloads/index.html), [SQL Developer 19.2.1](https://www.oracle.com/database/technologies/appdev/sql-developer.html), [Apache Studio 2](https://directory.apache.org/studio/) and [Oracle APEX 19.2](https://apex.oracle.com/en/)
	* Sample My HR and My IGA Applications and Demo Scenarios

**Note:** OIM and OIG are interchangeable terms and refer to the same product Oracle Identity Manager or Oracle Identity Governance.

SecureOracle v8.0 can be combined with Oracle Identity Cloud Service (IDCS) to showcase a hybrid identity management environment. When integrated with IDCS, the OIG component offers provisioning and governance services while IDCS provides access management services to cloud and on-prem applications.

The Oracle IAM Suite 12c R2 PS4 can be deployed using the Oracle IAM standard installation topology which is flexible and can be use as a starting point in production environments. The [Figure 1](#image-01) depicts a standard WebLogic Server domain that contains an Administration Server and one or more clusters containing one or more Managed Servers.

[](./images/idm12cps4-standard-topology.png)

## What is an Autonomous Database?
Oracle Autonomous Data Warehouse and Oracle Autonomous Transaction Processing are built around the market leading Oracle database and come with fully automated data warehouse and transaction processing specific features that deliver outstanding query performance. This environment is delivered as a fully managed cloud service running on optimized high-end Oracle hardware systems.  You don’t need to spend time thinking about how you should store your data, when or how to back it up or how to tune your queries. We take care of everything for you.

Watch our short video that explains key features in Oracle's Autonomous Database:

[](youtube:c-DUIePFKco)

Oracle’s Autonomous Database is the perfect quick-start service for fast data loading and sophisticated data reporting and analysis. Oracle manages everything for you so you can focus on your data.

## Workshop Objectives
- Get comfortable with Oracle's public cloud services
- Provision a new Autonomous Database instance on Shared Infrastructure
- Run sample queries against the sample data sets
- Load data from the object store
- Query external data from the object store
- Scale an ADB instance

## Lab Breakdown
- **Lab 1:** Log in to Oracle Cloud and access the Oracle Autonomous Data Warehouse console.
- **Lab 2:** Provision your first Autonomous Data Warehouse.
- **Lab 3:** Explore the provided sample data sets that come with your Autonomous Database.
- **Lab 4:** Upload files to the Oracle Cloud Infrastructure (OCI) Object Storage, create sample tables, load data into them from files on the OCI Object Storage, and troubleshoot data loads with errors.
- **Lab 5:** Query files on the Oracle Cloud Infrastructure Object Storage (OCI) directly without loading them to your database.
- **Lab 6:** Scale up your Oracle Autonomous Database service to have more CPUs.

**After reading the following workshop prerequisites, get started by clicking Lab 1 in the Contents menu on the right.**

## Workshop Prerequisites
This workshop requires an Oracle Cloud account. As a result of registering for LiveLabs, you will receive an email with instructions for accessing your account.

###Getting Help During This Workshop
If you have a question during this workshop then use the <a href="https://cloudcustomerconnect.oracle.com/resources/32a53f8587/summary" target="\_blank">**Autonomous Data Warehouse Forum**</a> on **Cloud Customer Connect** to post questions, connect with experts, and share your thoughts and ideas about Oracle Autonomous Data Warehouse.

Are you are completely new to the **Cloud Customer Connect**</a> forums? Visit our <a href="https://cloudcustomerconnect.oracle.com/pages/1f00b02b84" target="\_blank">**Getting Started forum page**</a> to learn how to best leverage community resources.

**You are all set; let's begin! Click Lab 1 in the Contents menu on the right.**

## Want to Learn More About Autonomous Database?

Use these links to get more information about Oracle Autonomous Database:

- <a href="https://www.oracle.com/database/autonomous-database.html" target="\_blank">Oracle Autonomous Database website</a>
- <a href="https://www.oracle.com/database/adw-cloud.html" target="\_blank">Oracle Autonomous Data Warehouse website</a>
- <a href="https://www.oracle.com/database/atp-cloud.html" target="\_blank">Oracle Autonomous Transaction Processing website</a>
- <a href="http://www.oracle.com/us/products/database/autonomous-dw-cloud-ipaper-3938921.pdf" target="\_blank">Oracle Autonomous Data Warehouse ipaper</a>
- <a href="https://docs.oracle.com/en/cloud/paas/autonomous-data-warehouse-cloud/index.html" target="\_blank">Oracle Autonomous Data Warehouse Documentation</a>
- <a href="https://docs.oracle.com/en/cloud/paas/autonomous-data-warehouse-cloud/videos.html" target="\_blank">Autonomous Data Warehouse Videos</a>
- <a href="https://docs.oracle.com/en/cloud/paas/autonomous-data-warehouse-cloud/tutorials.html" target="\_blank">Additional Autonomous Data Warehouse Tutorials</a>

## Acknowledgements

- **Author** - Nilay Panchal, ADB Product Management
- **Adapted for Cloud by** - Richard Green, Principal Developer, Database User Assistance
- **Last Updated By/Date** - Richard Green, April 2020

See an issue?  Please open up a request [here](https://github.com/oracle/learning-library/issues).  Please include the workshop name and lab in your request.
