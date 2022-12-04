# Intro
* SDDC : Use virtualization to enable central, cloud management for running, managing, and securing applications with a single software-defined data center (SDDC) solution. [SDDC](https://www.youtube.com/watch?v=8tGnN4VEZdc)
* NSX-T : NSX-T is a software-defined networking and security product by VMware. [More](https://www.techbytes.io/post/what-is-nsx-t)

# Whatis VMware Cloud Foundation
[VMware Cloud Foundation](https://www.vmware.com/products/cloud-foundation.html) is the hybrid cloud plateform for managing VM and Orchestrating containers.
![Alt text](img/vmware%20vCloud%20foundation.png)

# Workload Domains
* VMware Cloud Foundation consists of two types of Workload Domains that make up the Cloud Foundation Platform. These two Workload Domains are pools of logical resources. Each pool is a cluster or multiple clusters of ESXi hosts managed by an associated vCenter Server and NSX Manager. 
![Alt text](img/vmware%20Virtual%20Infrastructure%20VI.png)
## Management Domain
* There is one management domain that is used to manage the SDDC infrastructure components within a Cloud Foundation deployment.
* The management domain contains all of the management components of the SDDC Platform. This includes vCenter, vSAN, NSX-T Manager Controller Cluster, SDDC Manager, and any of the optional vRealize Suite components, such as vRealize Operations, vRealize Log Insight, and vRealize Automation.


## Workload Domain Virtual Infrastructure (VI)
* A Virtual Infrastructure (VI) Workload Domain is designed to run your business applications.
