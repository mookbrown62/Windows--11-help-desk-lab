Windows 11 Help Desk Troubleshooting & ServiceNow Lab

Project Overview

This home lab simulates a real-world Tier 1 Help Desk troubleshooting scenario. The objective was to diagnose a Windows 11 workstation experiencing slow performance and intermittent freezing, resolve the issue, verify system performance, and document the incident using ServiceNow.

Lab Environment

• Apple MacBook M1
• 16 GB RAM
• VirtualBox
• Windows 11 ARM64 Virtual Machine
• ServiceNow Personal Developer Instance
• Windows Task Manager
• Windows Update
• File Explorer

Help Desk Scenario

User Report:
The user reported that their Windows 11 computer was running slowly. Applications were taking longer than normal to open, and the computer would intermittently freeze for several seconds.

Troubleshooting Process

1. Checked System Performance

Opened Windows Task Manager and reviewed system resource utilization.

Initial readings:

• CPU: 2%
• Memory: 43%
• Disk: 0%
• Network: 0%

No abnormal resource utilization was identified.

2. Checked Available Storage

Reviewed the Windows C: drive in File Explorer.

• Total capacity: 69 GB
• Available space: 32.9 GB

The workstation had sufficient free storage, so low disk space was ruled out.

3. Reviewed Startup Applications

Used Task Manager to review applications configured to launch during Windows startup.

No significant startup application issues were identified.

4. Investigated Windows Update

Opened Windows Update and discovered that an important Windows security update was installed but pending a system restart.

The user was instructed to save all open work before restarting the workstation.

5. Restarted the Workstation

Restarted Windows to allow the pending security update to complete.

After the restart, Windows Update reported:

You’re up to date.

6. Verified System Performance

Task Manager was checked again after the restart.

Post-resolution readings:

• CPU: 1%
• Memory: 33%
• Disk: 0%
• Network: 0%

The user confirmed that system performance returned to normal and the intermittent freezing stopped.

ServiceNow Incident Management

The troubleshooting process was documented in a ServiceNow Personal Developer Instance.

Incident activities included:

• Creating an incident
• Selecting a caller
• Categorizing the issue
• Setting impact and urgency
• Documenting troubleshooting in Work Notes
• Recording the final resolution
• Resolving the incident

Resolution: A pending Windows security update required a restart. After completing the update and restarting the workstation, system performance returned to normal.

Skills Demonstrated

• Windows 11 troubleshooting
• Tier 1 Help Desk support
• Task Manager
• Performance monitoring
• Windows Update troubleshooting
• Storage troubleshooting
• Startup application troubleshooting
• ServiceNow incident management
• Ticket documentation
• Incident prioritization
• Root cause identification
• Resolution verification

Screenshots

Screenshots from the lab demonstrate:

1. Initial Task Manager performance
2. C: drive storage verification
3. Startup application review
4. Windows Update pending restart
5. Windows Update successfully completed
6. Post-resolution Task Manager performance
7. ServiceNow incident creation
8. ServiceNow troubleshooting documentation
9. ServiceNow incident resolution

Outcome

Successfully diagnosed and resolved the Windows 11 performance issue using a structured Help Desk troubleshooting process. The incident was documented and resolved in ServiceNow, demonstrating both technical troubleshooting and IT service management skills.


## Lab Screenshots

### 1. Initial Task Manager Analysis
Reviewed Task Manager to identify high CPU, memory, disk usage, and unnecessary processes.

![Task Manager Before](task%20manager%20before.JPEG)

### 2. Startup Application Review
Reviewed startup applications and disabled unnecessary programs to improve system startup performance.

![Startup Apps](Startup%20apps.PNG)

### 3. Windows Update Check
Checked Windows Update for pending operating system updates.

![Windows Update Pending](windows%20update%20pending.PNG)

### 4. Windows Update Completed
Installed available Windows updates and verified the system was fully updated.

![Windows Update Complete](Windows%20update%20complete.PNG)

### 5. Disk Storage Analysis
Reviewed disk storage to verify sufficient free space and identify potential storage-related performance issues.

![Disk Storage](disk%20storage.JPEG)

### 6. Post-Troubleshooting Verification
Rechecked Task Manager after troubleshooting to verify system performance.

![Task Manager After](task%20manager%20after.PNG)

### 7. ServiceNow Incident Resolution
Documented the troubleshooting process and resolution in ServiceNow and resolved the incident.

![ServiceNow Resolution](service%20now%20resolution.HEIC)
