# Week2Notes

### 2.1 A Brief History

“If computers of the kind I have advocated become the computers of the future, then computing may someday be organized as a public utility just as the telephone system is a public utility... The computer utility could become the basis of a new and important industry.”
John McCarthy,1961

“As of now, computer networks are still in their infancy, but as they grow up and become sophisticated, we will probably see the spread of 'computer utilities' …”
Leonard Kleinrock
Advanced Research Projects Agency Network

In the 1990s Salesforce.com pioneered the notion of bringing remotely provisioned services. In 2002 Amazon.com launched the AWS platform (Amazon Web Services), which provided remotely provisioned storage, computing resources and business functionality.
 
The term “Network Cloud” or “Cloud” was introduced in the 1990’s in the networking industry. In 2006 “cloud computing” emerged in the commercial arena, and during this time Amazon launched its Elastic Compute Cloud (EC2) services), and also Google Apps began providing browser-based enterprise applications.

A concise definition of cloud computing:

“Cloud computing is a specialized form of distributed computing that introduces utilization models for remotely provisioning scalable and measured resources.”
Forrester Research



### 2.2 Business Drivers
 #### Business Drivers
Before learning the layers of technologies that embody clouds, it is important to learn what led to their creation. Many of these business drivers are present in this section. 
It is important to know that these influences shaped clouds and the overall cloud computing from both ends. They have motivated organizations to adopt cloud computing and have motivated other organizations to be providers of cloud environments and cloud technology vendors.

#### Capacity Planning
It is the process of determining and fulfilling future demands of an organization’s IT resources, products and services. 
It represents the maximum amount of work that an IT resource is capable of delivering in a given period of time. Not knowing the capacity of an IT resource can cause a system becoming inefficient (over-provisioning) or unable to fulfill user needs (under-provisioning). 
Capacity planning is focused on minimizing the discrepancy to achieve predictable efficiency and performance.
Capacity planning strategies :
-Lead Strategy: adding capacity to an IT resource in anticipation of demand.
-Lag Strategy: adding capacity when the IT resource reaches its full capacity.
-Match Strategy: adding IT resource capacity in small increments, as demand increases.


#### Cost Reduction
Two costs need to be accounted for: the cost of acquiring new infrastructure, and the cost of its ongoing ownership. Operational overhead represents a considerable share of IT burgers, often exceeding up-in front investment costs.

Common forms of infrastructure-related operating overhead include the following:
-technical personnel required to keep the environment operational
-upgrades and patches that introduce additional testing and deployment cycles
-utility bills and capital expense investments for power and cooling
-security and access control measures that need to be maintained and enforced to protect infrastructure resources
-administrative and accounts staff that may be required to keep track of licenses and support arrangements


#### Organizational Agility
Businesses need the ability to adapt and evolve to successfully face change caused by internal and external factors. 
 “Organizational agility is the measure of an organization's responsiveness to change.”
changing business needs and priorities may require IT resources to be more available and reliable than before. 


### 2.3 Concepts and Terminology

#### Cloud
It refers to a distinct IT environment that is designed for the purpose of remotely provisioning scalable and measured IT resources.  The symbol of a cloud was commonly used to represent the Internet in a variety of specifications and mainstream documentation of Web-based architectures. This same symbol is now used to specifically represent the boundary of a cloud environment.

#### IT Resource
An IT resource is a physical or virtual IT-related artifact that can be either software based, such as a virtual server or a custom software program, or hardware-based, such as a physical server or a network device.
Cloud symbols can be used to define a boundary for a cloud-based environment that hosts and provisions a set of IT resources. 

#### On-Premise
This term is used to qualify an IT resource as an alternative to "cloud-based." An IT resource that is on-premise cannot be cloud-based, and vice-versa.
Key-Point
An on-premise IT resource can access and interact with a cloud-based IT resource.
An on-premise IT resource can be moved to a cloud, thereby changing it to a cloud-based IT resource.
Redundant deployments of an IT resource can exist in both on-premise and cloud based environments.


#### Scaling
Represents the ability of the IT resource to handle increased or decreased usage demands.
	Types of scaling:

##### Horizontal Scaling
Scaling out and Scaling in 
The horizontal allocation of resources is referred to as scaling out and the horizontal releasing of resources is referred to as scaling in. Horizontal scaling is a common form of scaling within cloud environments.

##### Vertical Scaling
Scaling up and scaling down
 The replacing of an IT resource with another that has a higher capacity is referred to as scaling up and the replacing an IT resource with another that has a lower capacity is considered scaling down. Vertical scaling is less common in cloud environments due to the downtime required while the replacement is taking place.

#### Cloud Service
It is any IT resource that is made remotely accessible via cloud. The term “service” within the context of cloud computing is especially broad. A cloud service can exist as a simple Web-based software program with a technical interface invoked via the use of a messaging protocol.

#### Cloud Service Consumer
The cloud service consumer is a temporary runtime role assumed by a software program when it accesses a cloud service.


### 2.4 Goals and Benefits
Cloud providers base their business model on the mass-adquisition of IT resources available to cloud customers. 

Common benefits to cloud consumer include:
		
	On demand access to pay-as-you-go
		
	Perception of having unlimited computing resources , reducing the need to prepare for provisioning
		
	Ability to add or remove IT resourcess at fine-grained level
		
	Abstraction of infrastucture so applications are not locked into devices or locations.
	
		
### 2.5 Risks and Challenges

##### Increased Security Vulnerabilities

it can be difficult to stablish a security architecture that spans such as trust boundary without introducing vulnerabilities

##### Reduce Operational Governance Control

 Reduced level of governance control can introduce risks associated with how the cloud provider operates its cloud

##### Limited Portability Between Cloud Providers

The lack of established industry standars within the cloud computing industry, public clouds are commonly propietary to various extents. It can be challenging to move from one cloud provider to another.

##### Multi-Regional Regulatory and Legal Issues

Some countries require different government regulations that specify different policies.


### Infrastructure as a Service (IaaS)

Is an instant computing infrastructure, provisioned and managed over the internet.

It helps avoid the expense anc complexity of buying and managing ohysucak servers and other datacenter infrastructure. 

##### Advantages of IAAS

Eliminates capital expense and reduces ongoing cost

Improves business continuity and disaster recovery

Innovate rapidly

Respond quicker to shifting business conditions

Focus on your core business

Increase stability, reliability, and supportability
 
Better security

Gets new apps to users faster
 
