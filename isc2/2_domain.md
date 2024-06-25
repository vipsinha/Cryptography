# Business Continuity
Business continuity planning (BCP)/continuity of operations planning (COOP) is one of the core responsibilities of the information security profession. Business continuity efforts are activities designed to keep a business running in the face of adversity.

## BCP Scope Definition
Here are three questions that can help define the scope:
- Which business activities will the plan cover?
- What types of systems will the plan cover?
- What types of controls will the plan consider?

## Business Impact Analysis (BIA)
- The BIA is an impact assessment that begins by identifying the organization’s mission-essential functions and then traces those backward to identify the critical IT systems that support those processes.
- Once planners have identified the affected IT sys- tems, they identify the potential risks, likelihood, and impacts to those systems as part of a risk assessment.

## BUSINESS CONTINUITY CONTROLS
- To help remediate potential availability issues. 
- It simply means that they are designed in such a way that the failure of a single component doesn’t bring down the entire system
- Single Point of Failure Analysis : The single point of failure (SPOF) analysis process provides security professionals with a mechanism to identify and remove single points of failure from their systems or processes. For example is to use a pair of firewalls, with one designated as the backup.
- Other Continuity Risks :
    - Sudden bankruptcy of a key vendor
    - Inability to provide the requisite computing or storage capacity
    - Utility service failures
    - Any other risk that IT management believes may disrupt operations
    -  highly skilled team member left the organization

## HIGH AVAILABILITY AND FAULT TOLERANCE
- High Availability : 
    - uses multiple systems to protect against failures. 
    - LOAD BALANCING : uses multiple systems to spread out the burden of providing service across those systems
- Fault Tolerance : 
    - It helps to protect a single system from failing in the first place by making it resilient in the face of technical failures
    - Storage : The second priority of many fault tolerance efforts is to protect against the failure of a single storage device.
        - RAID (redundant arrays of inexpensive disks) : two RAID technologies: disk mirroring and disk striping with parity.
            - RAID Level 1 (Disk Mirroring): Each disk has identical contents, and when the system writes any data to one disk, it automatically makes the same changes to the other disk
            - RAID 5 (Disk Striping with Parity) : In this approach, the system contains three or more disks and writes data across all of those disks but includes additional elements known as parity blocks spread across the disks
    - Networking Components : Networking components also can be single points of failure. Therefore, organizations should consider implementing redundancy at different points in the network
    - Redundancy Through Diversity : Use diverse technologies from a diverse set of vendors to avoid the failure of one tech- nology or vendor from critically impacting your environment

# Disaster Recovery
- Disaster recovery (DR) is a subset of business continuity activities designed to restore
a business to normal operations as quickly as possible following a disruption. 

## Disaster recovery plans (DRPs) 
It may include immediate measures that get operations working again temporarily, but the disaster recovery efforts are not finished until the organiza- tion is completely back to normal.

Remember, disaster recovery efforts conclude only when the organization is back to normal operations in its primary operating environment.

- Types of Disasters
    - environmental natural disaster
    - technological failure
    - a health emergency
    - hazard caused by humans

- Initial Response
    - Staffing : the organization should plan out disaster responsibilities as much as possible in advance and provide employees with training that prepares them to do their part during disaster recovery.
    - Communication : Responders must have secure, reliable means to communicate with each other and the organization’s leadership.

- Assessment
    After the immediate danger to the organization clears, the disaster recovery team shifts from initial response mode into assessment mode. 

- Disaster Recovery Metrics
    - recovery time objective (RTO) : targeted amount of time that it will take to restore a service to operation following a disruption
    - recovery point objective (RPO) : the maximum time period from which data may be lost as a result of a disaster.
    - recovery service level (RSL) : percentage of a service that must be available during a disaster. 

- Training and Awareness
    - All per- sonnel involved in disaster recovery efforts should receive periodic training about their role in the plan.

## BACKUPS
- Backup Media
    - Tape Backups
    - Disk Backups
    - Cloud Backups
- Backup Types
    - Full Backups
    - Differential backups : supplement full backups and create a copy of only the data that has changed since the last full backup
    - Incremental backups : They include only those files that have changed since the most recent full or incremental backup.
- DISASTER RECOVERY SITES
    - Hot sites : Less critical application
    - Warm sites : No real data
    - Cold sites : No server
    - Offsite Storage : Aggreement with other company

## TESTING DISASTER RECOVERY PLANS
- Read-Throughs
- Walk-Throughs
- Simulations
- Parallel Tests
- Full Interruption Tests

# Incident Response

- The four stages of the NIST incident response process are 
    - preparation, detection & analysis, 
    - containment, 
    - eradication & recovery, 
    - post-incident activity.
- Incident response teams 
    commonly include members from management, information security, physical security, legal counsel, public relations, human resources, along with technical subject matter experts.
- The highest priority of a first responder during incident response is to quickly contain the damage caused by the security incident.
- Security information and event management (SIEM) systems act as centralized log repository and analysis solutions.
