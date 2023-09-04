# AZ-900

**Type:** 🖥️ Azure
**Dates:** August 8, 2023
**Topic:** Azure, Certification, Course
**URL:** https://learn.microsoft.com/es-es/certifications/azure-fundamentals/

![AZ-900.png](./img/Banner%20-%20AZ-900.png)
# **Azure Fundamentals AZ-900**

- [Microsoft Certified: Azure Fundamentals - Certifications](https://learn.microsoft.com/es-es/certifications/azure-fundamentals/)
- **CERTIFICATION** | Link to the course: [link](https://www.notion.so/AZ-900-397a1b1a07ef49e9a404197742dee1d2?pvs=21)

---

**Index**

# Study Areas (Modules)

# Module 1 - Describe cloud concepts (15-20%)

## **[Episode 01: Cloud Computing, High Availability, Scalability, Elasticity, Agility, Fault Tolerance, and Disaster Recovery](https://youtu.be/Pt9LelJ0fL0)**

- Skills Learned
    - Describe what is **Cloud Computing**
    - Describe terms such as **High Availability**, **Scalability**, **Elasticity**, **Agility**, **Fault Tolerance**, and **Disaster Recovery**

### **Cloud Computing**

- Delivery model for services like ******storage, compute power, networking, analytics (performance data, telemetry)****** over the internet.
    - **Scalability** is a process of:
        - Allocating (adding)
        - Deallocating (removing)
        - **Resources**
            - V**ertical scaling**, scaling up / down, change the scale of your resource
            - H**orizontal scaling:** adding more resources to env
    - **Elasticity**
        - The ability to scale dynamically
    - **Agility**
        - The ability to react quickly, allocate and deallocate (scale) resources quickly
    - **Fault Tolerance**
        - The ability to remain up and running during component and service failures
    - **Disaster Recovery** is a serious disruption of services caused by a natural or human-induced causes
        - The ability to recover from an event that has taken down the service (disaster)
        - Use replication to avoid lose information
    - **High Availability**
        - The ability to keep services running for extended periods of time with very little downtime
        - Availability is a measure of system uptime for users/services
        - Uptime / uptime + downtime

## **[Episode 02: Principles of economies of scale](https://youtu.be/TMynEWIE3SM)**

- Skills Learned
    - Describe the **principles of economies of scale**

### **Economies of scale** cost per unit (service) lowers as the size of the company grows

## [**Episode 03: Capital Expenditure (CapEx) vs Operational Expenditure (OpEx) and their differences**](https://youtu.be/7KEygnLtRyE)

- Skills Learned
    - Describe the **differences between** **Capital Expenditure (CapEx)** and **Operational Expenditure (OpEx)**

### **Capital Expenditure (CapEx)**

- Own infrastructure
- Big initial investment
- Lost of maintenance required

### **Operational Expenditure (OpEx)**

- Rent infrastructure
- No initial investment
- Minimal maintenance
    - Operations team

| Cost Type | CapEx | OpEx |
| --- | --- | --- |
| Up front cost | Significant | None |
| Ongoing cost | Low | Based on usage |
| Tax Deduction | Over time | Same year |
| Early Termination | No | Anytime |
| Maintenance | Significant | Low |
| Value over time | Lowers | No change |

## [**Episode 04: Consumption-based model**](https://youtu.be/NdqncsMtryY)

- Skills Learned
    - Describe the **consumption-based model**

No upfront cost

No wasted resources

Pay for additional resources when needed

- **Compute** | **Storage** | **Network** + **time**
- Cost analysis

## **[Episode 05: IaaS, PaaS, SaaS and their differences](https://youtu.be/9CVBohl6w0Q)**

- Skills Learned
    - Describe **Infrastructure-as-a-Service** (IaaS)
    - Describe **Platform-as-a-Service** (PaaS)
    - Describe **Software-as-a-Service** (SaaS)
    - **Compare and contrast the three different service types**

### Service Models responsibilities

**As a service** means which party will manage the particular layer and all the layers below.

- **Software** layer consists the application (application code and set) & the application data
- **Platform** layer means all the supporting software and the operating system required to host the application
- **Infrastructure** layer consists hardware the infrastructure and virtualization required to host the platform

| Layer | Layer |
| --- | --- |
| Application | Software |
| Data | Software |
| Runtime | Platform |
| Middleware | Platform |
| Operating System | Platform |
| Virtualization | Infrastructure |
| Servers | Infrastructure |
| Networking | Infrastructure |
| Storage | Infrastructure |

### **Responsibility Matrix**

As such following table represents responsibilities

| Layer | On-Premises | IaaS | PaaS | SaaS |
| --- | --- | --- | --- | --- |
| Application | You | You | You | Cloud provider |
| Data | You | You | You | Cloud provider |
| Runtime | You | You | Cloud provider | Cloud provider |
| Middleware | You | You | Cloud provider | Cloud provider |
| Operating System | You | You | Cloud provider | Cloud provider |
| Virtualization | You | Cloud provider | Cloud provider | Cloud provider |
| Servers | You | Cloud provider | Cloud provider | Cloud provider |
| Networking | You | Cloud provider | Cloud provider | Cloud provider |
| Storage | You | Cloud provider | Cloud provider | Cloud provider |

### Azure Shared responsibility model

| On-Premises (Private Cloud) | Infrastructure (as a Service) | Platform (as a Service) | Software (as a Service) |
| --- | --- | --- | --- |
| Data & Access | Data & Access | Data & Access | Data & Access |
| Applications | Applications | Applications | Applications |
| Runtime | Runtime | Runtime | Runtime |
| Operating System | Operating System | Operating System | Operating System |
| Virtual Machine | Virtual Machine | Virtual Machine | Virtual Machine |
| Compute | Compute | Compute | Compute |
| Networking | Networking | Networking | Networking |
| Storage | Storage | Storage | Storage |
- **You manage**
- **Cloud provider manages**

![Untitled](AZ-900%20397a1b1a07ef49e9a404197742dee1d2/Untitled%201.png)

![Untitled](AZ-900%20397a1b1a07ef49e9a404197742dee1d2/Untitled%202.png)

## [**Episode 06: Public, Private, Hybrid cloud and their differences**](https://youtu.be/XlNR7myQydI)

- Skills Learned
    - Describe **Public cloud**
    - Describe **Private cloud**
    - Describe **Hybrid cloud**
    - Compare and contrast the three different cloud models

### **Public cloud**

- Everything runs on cloud provider hardware
- No local hardware
- Some services share hardware with other customers

| Advantages | Disadvantages |
| --- | --- |
| No CapEx | Security & Compliance |
| High availability & Agility | Ownership |
| Pay as you go pricing | Specific scenarios with unite business req. |
| No hardware maintenance |  |
| No deep technical skills required |  |

### **Private cloud**

- Everything runs in your own datacenter
- Self-service should be provided
- You maintain all the hardware

| Advantages | Disadvantages |
| --- | --- |
| Can support any scenario | Initial CapEx |
| Control over security | Limited Agility |
| Can meet any security & compliance requirements | IT skills & expertise are mandatory |

### **Hybrid cloud**

- Combine public & private clouds
- Great flexibility

| Advantages | Disadvantages |
| --- | --- |
| Great flexibility | Can be more expensive |
| Run legacy apps in private cloud | Complicated to manage |
| Utilize existing infrastructure | IT skills & expertise are mandatory |
| Meet any security requirements |  |

### Cloud Deployment Model

**Cloud Deployment Model** is simple a separation which describes where are the company resources deployed. Whenever this is in public cloud provider environment or private datacenter.

Below table presents high level deployment model separation

| Layer | Cloud Provider | Own Datacenter |
| --- | --- | --- |
| Public | ✅ | ✖ |
| Hybrid | ✅ | ✅ |
| Private | ✖ | ✅ |

# Module 2 - Describe core Azure services (30-35%)

## [**Episode 07: Azure Regions and Availability Zones**](https://youtu.be/C-nNw1mGwzE)

- Skills Learned
    - Describe **Data Centers**
    - Describe **Regions** and **Region Pairs**
    - Describe **Geographies**
    - Describe **Availability Zones**
    - Describe the **benefits and usage of core Azure architectural components** (Regions & Availability Zones)

### **Data Centers**

- **Physical facility**
- **Hosting** for group of networked servers
- Own power, cooling & networking infrastructure

### **Regions**

- **Geographical area** on the planet
- **One** but usually **more datacenters** connected with **low-latency network** (<2 milliseconds)
- **Location for** your **services**
- **Some services** are **available only in certain regions**
- **Some services** are **global services**, as such are not assigned/deployed in specific region
- **Globally available** with **50+** regions
- Specially **government regions** (US DoD Central, US Gov Virginia, etc.)
- Specially **partnered regions** (China East, China North)

### **Availability Zones**

- **Regional feature**
- Grouping of **physically separate** facilities
- Designed to **protect from data centers failures**
- If zone goes down ********************others continue working********************
- Two service categories
    - **Zonal** services (Virtual machines, disk, etc.)
    - **Zone-redundant** services (SQL, Storage, etc.)
- Not all regions are supported
- Supported region has three or more zones
- A zone is one or more data centers

### **Region pairs**

- **Each region** is **paired** with **another region** making it a **region pair**
- Region **pairs are static** and cannot be chosen
- Each **pair resides within** the **same geography***
    - Exception is Brazil South
- **Physical isolation** with **at least 300 miles distance** (When posible)
- **Some services** have **platform-provided replication**
- **Planned updates** across the pairs
- **********************************Data residency********************************** maintained for disaster recovery

**Geographies**

- **Discrete market**
- Typically **contains two or more regions**
- Ensures **data residency, sovereignty, resiliency**, and **compliance** requirements are met
- **Fault tolerant** to protect from region wide failures
- **Broken up** into areas
- Each **region belongs only to one Geography**

## [**Episode 08: Azure Resource Groups and Resource Manager**](https://youtu.be/gIhf-S7BCdo)

- Skills Learned
    - Describe **Resources**
    - Describe **Resource Groups**
    - Describe **Azure Resource Manager**
    - Describe the **benefits and usage of core Azure architectural components** (Azure Resource Manager & Resource Groups)

### **Resources**

- Objects ********************************************************used to manage services******************************************************** in Azure
- Represent **********************************service lifecycle**********************************
- All resources can be represented as a **JSON Template**

### **Resource Groups**

- (Grouping of resources) Logical container for all of your resources
- Holds **logically related** resources

**Organizing by:**

- **Type**
- **Lifecycle** (app, environment)
- **Department**
- **Billing**, **Location** or combination of those

### Additional information

- Each **resource must be in** one, and only one resource group
- Resource groups have their own **location assigned**
- Resources in the RGs **can reside in a different locations**
- Resources can be moved between the resources groups
- RGs **can’t be nested**
- **Orgnize based on your organization needs**

### Resource Manager

- **Management Layer** for all resources and resource groups
- ****************Unified**************** language
- **Controls** access and resources
- User can create via AZ-Portal, REST, PowerShell, CLI, SDK’s resources
- Azure Resource Manager, unified language

# **Describe some of the core products available in Azure**

## [**Episode 09: Azure Compute Services | Virtual Machine, VM Scale Set, App Service, Functions, Container Instances, Kubernetes Service**](https://youtu.be/inaXkN2UrFE)

- Skills Learned
    - Describe **products available for Compute** such as **Virtual Machines**, **Virtual Machine Scale Sets**, **App Services**, **Functions**, **Azure Container Instances** (ACI) and **Azure Kubernetes Service** (AKS)

### **Virtual Machines**

- Emulation of physical machines
- Different virtual hardware configuration per machine/app
- Different OS per machine/app

### **Virtual Machine Scale Sets**

- IaaS
- Set of identical virtual machines
- Built-in auto scaling features
- Designed for manual and auto-scaled workloads like web services, batch processing, etc.

### **Azure Container Instances** (ACI)

- Simple and fastes way to run a container in AZure
- PaaS
- Serverless Containers
- **Designed for**
    - Small and simple web apps/services
    - Background jobs
    - Scheduled scripts
- Use host OS
- Emulate operating system (VMs emulate hardware)
- Lightweight (no O)
    - Development Effort
    - Maintenance
    - Compute & storage requirements
- Respond quicker to demand changes
- Designed for almost any scenario

### **Azure Kubernetes Service** (AKS)

- Open-source container orchestration platform
- **PaaS**
- Highly scalable and customizable
- Designed for high scale container deployments (ANYTHING!)

### **App Services**

- Designed as enterprise grade web application service
- PaaS
- Support multiple programming languages and containers

### **Azure Functions (Function Apps)**

- PaaS
- Serverless
- Two hostings/pricing models
    - Consumption-based plan
    - Dedicated plan
- Designed for micro/nano-services
- Similar to App Services
- For small pieces of code as small web server

| Service | Configuration Control / Maintenance | Autoscaling | Min Nodes | Max Nodes | Scalability |
| --- | --- | --- | --- | --- | --- |
| Virtual Machines | ⭐⭐⭐⭐⭐ | No | 1 | 1 | ⭐ |
| Virtual Machine Scale Sets | ⭐⭐⭐⭐⭐ | Yes | 1 | 1000/600 | ⭐⭐⭐⭐⭐ |
| Azure Container Instances (ACI) | ⭐⭐⭐ | No | 0 | 20 | ⭐⭐ |
| Azure Kubernetes Service (AKS) | ⭐⭐⭐⭐ | Yes | 3 | 100 | ⭐⭐⭐⭐ |
| App Services | ⭐⭐ | Yes | 1 | 20/100 | ⭐⭐⭐ |
| Azure Functions | ⭐ | Yes | 0 | 200 | ⭐⭐⭐⭐ |

### Summary

- **Virtual machines (IaaS)**
    - Custom software, custom requirements, very specialized, high degree of control
- **VM Scale Sets (IaaS)**
    - Auto-scaled workloads for VMs
- **Container Instances (PaaS)**
    - Simple container hosting, easy to start
- **Kubernetes Services (PaaS)**
    - Highly scalable and customizable container hosting platform
- **App Service (PaaS)**
    - Web applications, a lot of enterprise web hosting features, easy to start
- **Functions (PaaS) (Function as a Service) (Serverless)**
    - Micro/nano-services, excellent consumption-based pricing, easy to start

## **[Episode 10: Azure Networking Services | Virtual Network, Load Balancer, VPN Gateway, Application Gateway, CDN](https://youtu.be/5NMcM4zJPM4)**

- Skills Learned
    - Describe **products available for Networking** such as **Virtual Network**, **Load Balancer**, **VPN Gateway**, **Application Gateway** and **Content Delivery Network**

Category of services with capability to:

- **Connect cloud** and **on-premise** resources
- **Protect** & **monitor** services
- Help with **application delivery**

### **Azure Virtual Network**

- Emulation of physical networking infrastructure
- Designed for **isolation**, **segmentation**, **communication**, **filtering**, **routing** between resources
- Scoped to a single region
- **VNET Peering** or **VPN Gateway** to allow cross VNet communication
- Segmented into one or more **subnets**
- **Subnets** are discrete section used for
    - Effective **address allocation** and
    - Network filtering via **Network Security Groups (NSG)** or **Application Security Groups (ASG)**

### **VPN Gateway**

Allows you to connect with the on-premises network

- On-premise to azure traffic over the public internet
- Cross-regional communication of azure virtual networks

### **Load Balancer**

**Scaling OUT (Horizontal)** adding machine with the same power

**Scaling UP (Vertical)** the same machine but with more power

- **Even** traffic **distribution**
- Supports both **inbound** and **outbound** scenarios
- **High-availability** and **scalability** scenarios
- Both **TCP** (Transmission control protocol) and **UDP** (User datagram protocol) applications
- **External** and **internal** traffic

### **Azure Application Gateway**

- Web traffic load balancer
- Web application firewall
- Redirection
- Session affinity
- URL Routing
- SSL Termination

### **Content Delivery Network (CDN)**

- Deliver web content to users
- Minimize latency
- POP (Points of presence) locations

### Summary

- **Azure Virtual Network -** Emulation**/**repesentation of physical networking in the cloud, grouping, filtering and segmentation of network related resources
- **VPN Gateway** - Connecting On-Premises with the Virtual Network and Virtual Networks with each other (remember about VNet Peering)
- **Load Balancer** - Even traffic distribution for non-HTTP (non-web) traffic
- **Azure Application Gateway** - Even traffic distribution for HTTP (web) traffic
- **Content Delivery Network (CDN)** - Global content caching & distribution to offload web applications and reduce latency

## [**Episode 11: Azure Storage Services | Blob, Disk, File and Archive**](https://youtu.be/_Qlkvd4ZQuo)

- Skills Learned
    - Describe **products available for Storage** such as **Blob Storage**, **File Storage**, **Queue Storage**, **Table Storage**, **Disk Storage**, and **Storage Tiers**

Types of data

- Structured:
- Semi-structure:
- Unstructured: bin files

### **Blob Storage**

**B**inary **L**arge **Ob**ject 

- Designed for storage of **files of any kind**
- Three **storage tiers**
    - **Hot** - frequently accessed data
    - **Cool** - infrequently accessed data (lower availability, high durability)
    - Archive - rarely (if-ever) accessed data
- Containers with blobs

### **Queue Storage**

- Storage for small pieces of data (**messages**)
- Designed for **scalable asynchronous processing**

### **Table Storage**

- Storage for semi-structured data (NoSQL)
    - No need for foreign joins, foreign keys, relationships or strict schema
    - Designed for fast access
- Many programming interfaces and SDKs

### **File Storage**

- File storage with share and files accessing the data through **SMB** protocol
- Storage for **files** accessed via **shared drive** protocols
- Designed to extend **on-premise** file shares or implement **lift-and-shift** scenarios

### **Azure Storage Account**

- **Blob**, **table**, **queue** and **file** storage are part of Azure Storage Account, is a collection of services
- Used to store
    - **files**
    - **messages**
    - **semi-structured** **data**
- **Highly scalable** (Up to petabytes of data)
- **Highly durable** (99.999999999% - 11 nines, up to 16 nines)
- **Cheapest** per GB Storage

### **Azure Disk Storage**

- Its used to VM’s
- Persistent storage for virtual machines
- Different
    - Sizes
    - Types
    - Performance tiers

### **Storage Tiers**

## **Summary**

- **Azure Storage Account** - Highly scalable and highly durable storage service consisting group of smaller services (Blob, file, queue and table storage services)
- **Azure Blob Storage** - General purpose (Blob) file storage, first any scenario
- **Azure File Storage** - File share service in the cloud, lift-and-shift scenarios
- **Azure Queue Storage** - Service for storing small messages for asynchronous processing
- **Azure Table Storage** - Scalable NoSQL storage service for semi-structured data

## [**Episode 12: Database Services | Cosmos DB, SQL Database, SQL DB for MySQL and PostreSQL, Database Migration Service**](https://youtu.be/RqD4nMyBazU)

- Skills Learned
    - Describe the benefits and usage of **Cosmos DB**, Azure **SQL Database**, Azure **Database for MySQL**, Azure **Database for PostgreSQL**, and **SQL Managed Instance**

### **Cosmos DB**

- **Globally distributed** NoSQL semi-structured data
- **Schema-less**
- **Multiple API** (SQL, MongoDB, Cassandra, Gremlin, Table Storage)
- Designed for
    - **Highly responsive** (Real time) applications with super low latency responses <10ms
    - **Multi-regional** applications

### Azure SQL Product Family

- **SQL Database**
    - Relational database service in the cloud (PaaS)(DBaaS - DB as a Service)
    - **Structured data service** defined using schema and relationships
    - **Rich Query Capabilities** (SQL)
    - **High-performance**, **reliable**, **fully managed** and **secure** database for building applications
- **Managed Instance**
- **SQL Data Ware House**
- **SQL VM**
- **Database for MySQL**
- **Database for PostgreSQL**

### **SQL Managed Instance**

### Summary

- **Azure Cosmos DB** - Globally distributed NoSQL Database, low latency, multi-master perfect for serverless
- **Azure SQL Database** - Reliable relational database based on SQL Server
- **Azure Database for MySQL** - Azure SQL version for MySQL database enginer
- **Azure Database for PostgreSQL** - Azure SQL version for PostgreSQL database engine
- **Azure SQL Managed Instance** - Fully fledged SQL Server managed by cloud provider
- **Azure SQL on VM** - Fully fledged SQL Server on IaaS
- **Azure SQL DW (Synapse)** - Massively Parallel Processing (MPP) version of SQL Server

## [**Episode 13: Azure Marketplace**](https://youtu.be/ersOL_o_lzc)

- Skills Learned
    - Describe the **Azure Marketplace**

Key characteristics:

- **Azure shop**
- **First** and **third-party** products
- **IaaS**, **PaaS** and **SaaS**

Commercial Marketplace

**Microsoft AppSource** (Business users)

- Azure
- Power BI
- Dynamics 365
- Microsoft 365

**Azure Marketplace** (Developers & IT Pros)

- Azure

# **Describe some of the solutions available on Azure**

## [**Episode 14: Azure IoT Services | IoT Hub, IoT Central, Azure Sphere**](https://youtu.be/RHkqFxJWhr8)

- Skills Learned
    - Describe the benefits and usage of
        - **Internet of Things (IoT) Hub**
        - **IoT Central**
        - **Azure Sphere**

### **Internet of Things (IoT) Hub**

- Managed service for bi-directional communication
- PaaS
- Hihgly secure, scalable and reliable
- Integrates with a lot of Azure Services
- Programable SDKs for popular languages (C, C#, Java, Python, Node.js)
- Multiple protocols (HTTPS, AMQP, MQTT)

### **IoT Central**

- IoT App Platform - SaaS
- Industry specific app templates
- No deep technical knowledge required
- Service for connecting, management and monitoring IoT devices
- Highly secure, scalable and reliable
- Built on top of the IoT Hub service and 30+ other services

### **Azure Sphere**

- Secure end-2-end IoT Solutions
    - Azure Sphere certified chips MCUs
    - Azure Sphere OS based on Linux
    - Azure Secuirty Service trusted device-to-cloud communication

### Summary

- **IoT Hub** - Managed service for bi-directional communication with IoT devices, PaaS
- **IoT Central** - IoT application platform, dozen of functionalities, Saas
- **Azure Sphere** - end-2-end approach for building secure IoT solutions

## [**Episode 15: Azure Big Data and Analytics Services | Synapse Analytics (SQL Datawarehouse), HDInsight & Databricks**](https://youtu.be/JUQXx0R0RfE)

- Skills Learned
    - Describe the benefits and usage of
        - **Azure Synapse Analytics**
        - **HDInsight**
        - **Azure Databricks**

### What is big data

**Big data** Is a field of technology that helps with **extraction**, **processing** and **analysis** of information that is **too large** or **complex** to deal with traditional software.

**Velocity**

- Real time
- Near real time
- Periodic
- Batch

**Volume**

- Megabyte
- Gigabyte
- Terabyte
- Petabyte

**Variety**

- Table
- Database
- Photo | Audio
- Video | Social

### **Azure Synapse Analytics**

- **Big data analytics platform** SaaS
- **Multiple components**
    - **Spark**
    - **Synapse SQL**
        - SQL Pools (dedicated — pay for provisioned performance)
        - SQL on-demand (ad-hoc — pay for TB processed
    - **Synapse Pipelines** (Data Factory - ETL)
    - **Studio** (unified experience)

### **HDInsight**

- Flexible multi-purpose big data platform PaaS
- Multiple technologies supported (Hadoop, Spark, Kafka, HBase, Hive, Storm, Machine Learning)

### **Azure Databricks**

- Big data collaboration platform (PaaS)
- Unified workspace for notebook, cluster, data, access management and collaboration
- Based on Spark
- **Integrates** very well with common Azure data services

### Summary

- **Azure Synapse Analytics -** Modern workspace for end-2-end enterprise data warehousing & analytics with a lot of integrated tools like DAta Factory, Spark, SQL, etc.
- **HDInsight -** Fully-managed open source analytics service with a lot of supported frameworks & tools like Hadoop, Spark, Kafka, Hive, etc.
- **Azure Databricks** - Apache Spark based analytics platform for data transofmration and collaborative analytics.

## [**Episode 16: Azure Artificial Intelligence (AI) Services | Machine Learning Studio and Service**](https://youtu.be/8aMzR8iaB9s)

- Skills Learned
    - Describe **Artificial Intelligence (AI) and products that are available for AI** such as Azure **Machine Learning Service and Studio**

### **What is AI**

**Artificial Intelligente** (**AI**) is the simulation of human intelligence & capabilities by compute software

### **What is ML**

**Machine Learning** (**ML**) ****is a subcategory of AI where a compute software is “**taught**” to **draw conlusions** and **make predictions** from **data**.

### Azure **Machine Learning Service and Studio**

- Cloud-based platform for **creating**, **managing** and **publishing** machine learning **models**
- **PaaS**
- **ML Workspace** - Top level resource
- **ML** **Studio** - Web portal for e2e users development
- Features
    - **Notebooks** — using Python and R
    - **Automated ML** — run multiple alhorithms | parameters combinations, choose the best model
    - **Designer** — graphical interface for no-code development
    - **Data & Compute** — management of storage and compute resources
    - **Pipelines** — orchastrate model training, deployment and management tasks

## [**Episode 17: Azure Serverless Computing Services | Functions, Logic Apps, Event Grid**](https://youtu.be/ansa4M7iTmg)

- Skills Learned
    - Describe **Serverless computing** and Azure **products** that are available for serverless computing such as **Azure Functions**, **Logic Apps**, and **Event Grid**

### What is Serverless computing

**Serverless computing** is cloud-hosted execution environment that allows customers to **run their applications** in the cloud while **completely abstracting underlying infrastructure**

### **Azure Functions**

- **Serverless coding platform** FaaS
- Designed for **nano-service** architectures and **event-based** applications
- **Scales** up and down very **quickly**
- High scalable
- **Support popular languages** and **frameworks** (.Net & .Net Core, Java, Jode.js, Pyhon, PowerShell, etc.)

### Azure **Logic Apps**

- Serverless enterprise integration service PaaS
- 200+ connectors for popular services
- Designed for orquestration of
    - Business processes
    - Integration workflows for applications, data, systems and services
- No-code solution

### **Event Grid**

- Fully managed serverless event routing service
- Uses **publish-subscribe** model
- Designed for event-based and near-real time applications
- Support dozen of **build-in events** from most common **Azure Services**

### Summary

- **Azure Functions -** application development platform for nano-services and event-based application using popular languages | frameworks
- **Logic Apps -** enterprise integration services for orchestration of business and application workflows
- **Event Grid -** scalable event routing service for integration and near-real time applications

## [**Episode 18: Azure DevOps Solutions | Azure DevOps, DevTest Labs**](https://youtu.be/8M4DN9hjAeY)

- Skills Learned
    - Describe **DevOps solutions** available on Azure such as **Azure DevOps** and Azure **DevTest Labs**

### **Azure Devops**

Collection of services for building solutions using DevOps practices

Services inlcuded:

- **Boards**: tracking work
- **Repos**: code collaboration and verioning with GIT
- **Pipelines**: building CI/CD workflows (build, test and deploy apps)
- **Artifacts**: manage project deliverables
- **Test Plans**: manual and exploratory testing

Evolved from **TFS** (Team foundation server), throught **VSTS** (Visual Studio Team Service)

### **Azure DevTest Labs**

- Services **sandbox** **environment** for **developers/testers** (PaaS)
- Quick setup of **self-managed virtual** **machines**
- **Preconfigured templates** for VMs
- Plenty of additional **artifacts** (tools, apps, custom actions)
- Lab ******************policies****************** (quotas, sizes, auto-shutdown)
- Share and automate labs via custom iamges
- Premade plugins/Api/tools for CI/CD pipeline automation

### Summary

- **Azure DevOps** — e2e platform for building CI/CD pipelines, code versioning, tracking work and managing project deliverables
- **Azure DevTest Labs** — cloud-based environments for developers and testers with self-serve environments, reusable templates, cost management and multiple integrations

# **Describe Azure management tools**

## **[Episode 19: Azure Tools | Portal, PowerShell, CLI and CloudShell](https://youtu.be/8JHY0xPssb8)**

- Skills Learned
    - Describe **Azure tools** such as **Azure Portal**, **Azure PowerShell**, **Azure CLI** and **Cloud Shell**

### **Azure Portal**

- Public **web-based interface** for management of Azure platform
- Designed for **self-service**
- Customizable
- Simple task

### **Azure PowerShell**

- PowerShell and **module**
- Designed for **automation**
- Multi-platform with PowerShell Core
- Simple to use:
    - Connect-AzAccount — Log into Azure
    - Get-AzResourceGRoup — List resource groups
    - New-AzResourceGroup — Create new resource group
    - New-AzVm — Create virtual machine

### **Azure CLI**

- Command Line Interface for Azure
- Designed for automation
- Multi-platform (Python)
- Simple to use
- Native OS terminal scripting

### **Azure Cloud Shell**

- Cloud-based **scripting** **environment**
- Completely **free**
- Supports both Azure **PowerShell** and Azure **CLI**
- Dozen of **additional tools**
- Multiple client interfaces

### Summary

- **Azure Portal —** Web based portal for self-service management of Azure platform
- **Azure PowerShell —** Automation module for PowerShell
- **Azure CLI —** automation module for terminal
- **Azure Cloud Shell —** free cloud-based scripting environment

## **[Episode 20: Azure Advisor](https://youtu.be/58_6MkB2znI)**

- Skills Learned Describe **Azure Advisor**

### **Azure Advisor**

Personalized consultand service

- Designed to provide **recommendations** and **best practices** for:
    - **Cost** (SKU Sizes, idle services, reserved instances, etc)
    - **Security** (M
    - **Reliability** (
    - **Performance** (
    - **Operational Excellence** (
- **Actionable** recommendations
- Free!

### Summary

**Azure Advisor —** 

# Module 3 - **Describe Security, Privacy, Compliance, and Trust (25-30%)**

## **Describe securing network connectivity in Azure**

## **[Episode 21: Security Groups | NSG and ASG | Network Security Groups and Application Security Groups](https://youtu.be/w8H5fWBHddA)**

- Skills Learned
    - Describe **Network Security Groups** (NSG)
    - Describe **Application Security Groups** (ASG)

### **Network Security Groups** (NSG)

- Designed to **filter traffic** to (**inbound**) and from (**outbound**) Azure resources located in Azure **Virtual Network**
- Filtering controlled by **rules**
- Ability to have **multiple** inbound and outbound **rules**
- Rules are created by specifying
    - **Source**/**destination** (Ip addresses, service tags, application security groups)
    - **Protocol** (TCP, UDP, any)
    - **Port** (or Port Ranges, ex. 3389 — **RDP**, 22 — **SSH**, 80 **HTTP**, 443 **HTTPS**)
    - **Direction** (inbound or outbound)
    - **Priority** (order of evaluation)

### **Application Security Groups** (ASG)

- Feature that allows **grouping of virtual machines** located in AZure Virtual Network
- Designed to **reduce** the **maintenance effort** (assign ASG instead of the explicit IP address)

### **Summary**

- Describe **Network Security Groups** (NSG) - Filtering of incoming and outgoing traffic for virtual network resources
- Describe **Application Security Groups** (ASG) - Logical grouping of virtual network resources for easier maintenance

## **[Episode 22: User-defined Routes (UDR)](https://youtu.be/BUH9kVTrM-8)**

- Skills Learned
    - Describe **User-defined Routes** (UDR)

### What is routing?

Process of finding/selecting a path for a traffic in one or across multiple networks.

### **User-defined Routes** (UDR)

- **Custom** (user-defined, static) **routes** (UDRs)
- Designed to **override Azure default routing** or **add new** routes
- Managed via Azure **Route Table** resource
- **Associated with** a zero or more Virtual Network **subnets**

## **[Episode 23: Azure Firewall](https://youtu.be/VIEaz869njk)**

- Skills Learned
    - Describe **Azure Firewall**

## **[Episode 24: Azure DDoS Protection](https://youtu.be/MUVFMF9DgM0)**

- Skills Learned
    - Describe **Azure DDoS Protection**

# **Describe core Azure Identity services**

## **[Episode 25: Azure Identity Services | Identity, Authentication, Authorization & Azure AD](https://youtu.be/b_WIjY-burU)**

- Skills Learned
    - Describe the **difference between authentication** and **authorization**
    - Describe **Azure Active Directory**
    - Describe Azure **Multi-Factor Authentication**

# **Describe security tools and features of Azure**

## **[Episode 26: Azure Security Center and usage scenarios](https://youtu.be/tyztKP9rszU)**

- Skills Learned
    - Describe **Azure Security Center**
    - Describe **Azure Security Center** usage scenarios

## **[Episode 27: Azure Key Vault](https://youtu.be/AA3yYg9Zq9w)**

- Skills Learned
    - Describe **Azure Key Vault**

# **Describe Azure governance features**

## **[Episode 28: Role-Based Access Control (RBAC)](https://youtu.be/4v7ffXxOnwU)**

- Skills Learned
    - Describe the functionality and usage of **Role-Based Access Control (RBAC)**

## **[Episode 29: Resource Locks](https://youtu.be/eDH20Ve0eI0)**

- Skills Learned
    - Describe the functionality and usage of **resource locks**

## **[Episode 30: Tags](https://youtu.be/J40eJR4qQ0w)**

- Skills Learned
    - Describe the functionality and usage of **tags**

## **[Episode 31: Azure Policy](https://youtu.be/9WO4EBgUJXk)**

- Skills Learned
    - Describe the functionality and usage of **Azure Policy**

## **[Episode 32: Azure Blueprints](https://youtu.be/3rSCnAZPNfo)**

- Skills Learned
    - Describe the functionality and usage of **Azure Blueprints**

## **[Episode 33: Cloud Adoption Framework](https://youtu.be/d6usiB4MKq8)**

- Skills Learned
    - Describe the **Cloud Adoption Framework** for Azure

# **Describe privacy and compliance resources**

## **[Episode 34: Core tenets of Security, Privacy, and Compliance](https://youtu.be/zBzsDYZw98M)**

- Skills Learned
    - Describe the purpose of the **Microsoft Privacy Statement**, **Online Services Terms** (OST) and **Data Protection Amendment** (DPA)
    - Describe the purpose of the **Trust Center**
    - Describe the purpose of the **Azure compliance** documentation
    - Describe the purpose of **Azure Sovereign Regions** (Azure Government cloud services and Azure China cloud services)

# Module 4 - **Describe Azure cost management and Service Level Agreements and lifecycle (10-15%)**

# **Describe methods for planning and managing costs**

## **[Episode 35: Cost Affecting Factors](https://youtu.be/Z8wvj_oe97M)**

- Skills Learned
    - Identify **factors that can affect costs** (**resource types**, **services**, **locations**, **ingress** and **egress traffic**)

## **[Episode 36: Cost Reduction Methods and Pricing, TCO Calculators](https://youtu.be/ZV2bfoqFpZ8)**

- Skills Learned
    - Identify **factors that can reduce costs** (reserved instances, reserved capacity, hybrid use benefit, spot pricing)
    - Describe the functionality and usage of the **Pricing calculator** and the **Total Cost of Ownership (TCO) calculator**

## **[Episode 37: Azure Cost Management](https://youtu.be/7w88KBVesPI)**

- Skills Learned
    - Describe the functionality and usage of **Azure Cost Management**

# **Describe Azure Service Level Agreements (SLAs) and service lifecycles**

## **[Episode 38: Azure Service Level Agreement (SLA)](https://youtu.be/WuzpcMZ1UxI)**

- Skills Learned
    - Describe the purpose of an Azure **Service Level Agreement** (SLA)
    - Identify actions that can impact an **SLA** (i.e. Availability Zones)

## **[Episode 39: Service lifecycle in Azure](https://youtu.be/J4HzsmuClV0)**

- Skills Learned
    - Describe the **service lifecycle in Azure** (Public Preview and General Availability)

# Wrong answer from AZ Tests

- Increasing the capacity of an application by adding additional virtual machine is called horizontal scaling
- You have an Azure virtual machine that is accessed only between 9:00 and 17:00 each day. What should you do to minimize costs but preserve the associated hard disks and data?
    - Deallocate the virtual machine.
- MFA > Azure Policy
- Provisioning JSON Format ARM Templates
- Azure Advisor > recommendations to improve reliability, security, performance and cost reduction

# Other

- whizlabs simulator