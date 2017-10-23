## Welcome to Project Q (sun4v)

This contains some of the content from the Kenai.com site that was closed.


# Hypervisor/Sun4v Reference Materials

## OpenSPARC Hypervisor

* [GitHub Repo](https://github.com/sun4v/hypervisor/)

## Architecture Specifications

* [UltraSPARC Virtual Machine Specification v3 current draft](downloads/hypervisor-api-3.0draft7.pdf) (PDF)

* [UltraSPARC Virtual Machine Specification v2.0](downloads/Hypervisor-api-2.0b.pdf) (PDF)

* [UltraSPARC Architecture specifications](http://www.oracle.com/technetwork/systems/opensparc/index.html)

## ARC Cases

The following is a list of sun4v-related [ARC](http://opensolaris.org/os/community/arc/) cases.  A request has been made to open them for public access via the [OpenSolaris ARC community](http://opensolaris.org/os/community/arc/).  This list will be updated with links to the open cases, links with errors point to as-of-yet un-opened cases.

Update: arc.opensolaris.org appears to be gone so all of the links below are useless.  The canonical location of the below list is now on the cpubringup wiki inside the Oracle network.  This version will no longer be updated.

### Core sun4v
* [FWARC 2004/510](http://arc.opensolaris.org/caselog/FWARC/2004/510) Project Q Umbrella (sun4v/hypervisor)
* [FWARC 2005/116](http://arc.opensolaris.org/caselog/FWARC/2005/116) sun4v core APIs
* [FWARC 2005/251](http://arc.opensolaris.org/caselog/FWARC/2005/251) diagnostic APIs
* [FWARC 2005/499](http://arc.opensolaris.org/caselog/FWARC/2005/499) sun4v core version API
* [FWARC 2006/052](http://arc.opensolaris.org/caselog/FWARC/2006/052) sun4v version API update
* [FWARC 2005/367](http://arc.opensolaris.org/caselog/FWARC/2005/367) sun4v watchdog API
* [FWARC 2006/093](http://arc.opensolaris.org/caselog/FWARC/2006/093) sun4v watchdog API update
* [FWARC 2006/199](http://arc.opensolaris.org/caselog/FWARC/2006/199) sun4v watchdog API fn correction
* [FWARC 2008/134](http://arc.opensolaris.org/caselog/FWARC/2008/134) Hypervisor support for Hardware Watchdog Timer
* [FWARC 2006/323](http://arc.opensolaris.org/caselog/FWARC/2006/323) sun4v console read/write hv APIs
* [FWARC 2006/473](http://arc.opensolaris.org/caselog/FWARC/2006/473) sun4v guest state API update
* [FWARC 2006/542](http://arc.opensolaris.org/caselog/FWARC/2006/542) Guest State Supported CIF
* [FWARC 2006/074](http://arc.opensolaris.org/caselog/FWARC/2006/074) sun4v interrupt cookies

### Machine Description
* [FWARC 2005/115](http://arc.opensolaris.org/caselog/FWARC/2005/115) machine description
* [FWARC 2006/110](http://arc.opensolaris.org/caselog/FWARC/2006/110) Domain Services MD node and other misc properties
* [FWARC 2006/545](http://arc.opensolaris.org/caselog/FWARC/2006/545) max-vcpu and mondo-latency MD properties
* [FWARC 2007/480](http://arc.opensolaris.org/caselog/FWARC/2007/480) sun4v Cpu MD node property updates
* [FWARC 2007/070](http://arc.opensolaris.org/caselog/FWARC/2007/070) Machine Description IO Device Node Definitions
* [FWARC 2007/386](http://arc.opensolaris.org/caselog/FWARC/2007/386) Machine Description IO Device Node Definition Updates
* [FWARC 2007/122](http://arc.opensolaris.org/caselog/FWARC/2007/122) VIO MD node updates
* [FWARC 2007/260](http://arc.opensolaris.org/caselog/FWARC/2007/260) Machine Description Latency Node Descriptions
* [FWARC 2007/689](http://arc.opensolaris.org/caselog/FWARC/2007/689) LDOMs support for RN (MD rng property update)
* [FWARC 2008/270](http://arc.opensolaris.org/caselog/FWARC/2008/270) PCI Address MD Node Properties
* [FWARC 2008/563](http://arc.opensolaris.org/caselog/FWARC/2008/563) Virtual Domain Service MD nodes and misc. properties
* [FWARC 2008/349](http://arc.opensolaris.org/caselog/FWARC/2008/349) New MD Nodes to Support I/O Reconfiguration for Failover Conditions.
* [FWARC 2009/300](http://arc.opensolaris.org/caselog/FWARC/2009/300) CPU MD node property for real address bits
* [FWARC 2009/521](http://arc.opensolaris.org/caselog/FWARC/2009/521) Bandwidth Resource Control
* [FWARC 2009/680](http://arc.opensolaris.org/caselog/FWARC/2009/680) Domain UUID Property
* [FWARC 2010/034](http://arc.opensolaris.org/caselog/FWARC/2010/034) Updates to Virtual CPU node "compatible" property
* [FWARC 2011/121](http://arc.opensolaris.org/caselog/FWARC/2011/121) New "mtu" property in "iov-device-class-props" nodes in VIO MD specification
* [FWARC 2011/312](http://arc.opensolaris.org/caselog/FWARC/2011/312) Deprecate MD property "intr" on T3/T4 platforms

### PRI
* [FWARC 2006/700](http://arc.opensolaris.org/caselog/FWARC/2006/700) Physical Resource Inventory (PRI)
* [FWARC 2007/138](http://arc.opensolaris.org/caselog/FWARC/2007/138) Updates to PRI structures
* [FWARC 2008/467](http://arc.opensolaris.org/caselog/FWARC/2008/467) PRI Specification modification
* [FWARC 2008/768](http://arc.opensolaris.org/caselog/FWARC/2008/768) PRI Versioning
* [FWARC 2009/061](http://arc.opensolaris.org/caselog/FWARC/2009/061) PRI: "path" property requirement
* [FWARC 2009/169](http://arc.opensolaris.org/caselog/FWARC/2009/169) "max_guest_dependencies" property requirement in PRI
* [FWARC 2009/281](http://arc.opensolaris.org/caselog/FWARC/2009/281) PRI clarifications for hostbridge id & PCI-E root complex node
* [FWARC 2009/644](http://arc.opensolaris.org/caselog/FWARC/2009/644) Updates to PRI for Static Direct IO (PCI-E Virtualization)
* [FWARC 2010/066](http://arc.opensolaris.org/caselog/FWARC/2010/066) PRI enhancements to support Memory Power Management & Power Cap
* [FWARC 2010/090](http://arc.opensolaris.org/caselog/FWARC/2010/090) Update to PRI to remove erroneous rcid property
* [FWARC 2010/185](http://arc.opensolaris.org/caselog/FWARC/2010/185) PRI Changes for Direct Attached Disks
* [FWARC 2010/371](http://arc.opensolaris.org/caselog/FWARC/2010/371) Update to PRI Specification to clarify the definition of certain component node properties
* [FWARC 2011/115](http://arc.opensolaris.org/caselog/FWARC/2011/15)  PRI updates for SRIOV Root Complex Resource Allocation
* [FWARC 2011/272](http://arc.opensolaris.org/caselog/FWARC/2011/272) PRI update to specify maximum number of HV memory blocks

### I/O
* [FWARC 2005/112](http://arc.opensolaris.org/caselog/FWARC/2005/112) io APIs
* [FWARC 2006/474](http://arc.opensolaris.org/caselog/FWARC/2006/474) pci io hv iommu attributes update
* [FWARC 2009/050](http://arc.opensolaris.org/caselog/FWARC/2009/050) Hypervisor API Improvements for VPCI DMA Sync
* [FWARC 2009/213](http://arc.opensolaris.org/caselog/FWARC/2009/213) dma-sync-options property under PCI Express Root Complex
* [FWARC 2009/268](http://arc.opensolaris.org/caselog/FWARC/2009/268) minor clarifications to sun4v io_api.txt

* [FWARC 2009/537](http://arc.opensolaris.org/caselog/FWARC/2009/537) Static Direct I/O HV IO API Updates 
* [FWARC 2009/536](http://arc.opensolaris.org/caselog/FWARC/2009/536) Static Direct I/O Bridge Emulation 
* [FWARC 2009/535](http://arc.opensolaris.org/caselog/FWARC/2009/535) Static Direct I/O Loaned Device Node specification 
* [FWARC 2010/137](http://arc.opensolaris.org/caselog/FWARC/2010/137) sun4v io api vpci v2.0 
* [FWARC 2011/123](http://arc.opensolaris.org/caselog/FWARC/2011/123) PF Device Binding update
* [FWARC 2011/124](http://arc.opensolaris.org/caselog/FWARC/2011/124) SRIOV VF firmware spec
* [FWARC 2011/125](http://arc.opensolaris.org/caselog/FWARC/2011/125) SRIOV PF emulation spec

### Error Handling
* [FWARC 2006/200](http://arc.opensolaris.org/caselog/FWARC/2006/200) sun4v error handling
* [FWARC 2006/201](http://arc.opensolaris.org/caselog/FWARC/2006/201) sun4v error handling update
* [FWARC 2009/070](http://arc.opensolaris.org/caselog/FWARC/2009/070) sun4v error handling update (ATTR.ST_STATE addition)

### Niagara Platform
* [FWARC 2005/173](http://arc.opensolaris.org/caselog/FWARC/2005/173) Hypervisor Service API
* [FWARC 2005/164](http://arc.opensolaris.org/caselog/FWARC/2005/164) sun4v Niagara CPU API
* [FWARC 2005/467](http://arc.opensolaris.org/caselog/FWARC/2005/467) Niagara mmustat HV API

### Niagara 2 Platform
* [FWARC 2006/556](http://arc.opensolaris.org/caselog/FWARC/2006/556) NIU/SIU Device Tree Bindings and Machine Description Definitions
* [FWARC 2006/524](http://arc.opensolaris.org/caselog/FWARC/2006/524) Niagara2 Network Interface Unit Hypervisor API
* [FWARC 2006/429](http://arc.opensolaris.org/caselog/FWARC/2006/429) Niagara2 Perf Regs HV API
* [FWARC 2006/498](http://arc.opensolaris.org/caselog/FWARC/2006/498) Niagara2 PIU Perf Counters HV API
* [FWARC 2008/248](http://arc.opensolaris.org/caselog/FWARC/2008/248) Niagara2 NIU Hypervisor API Extensions
* [FWARC 2008/402](http://arc.opensolaris.org/caselog/FWARC/2008/402) Niagara2 NIU Hypervisor API Extensions v2.0
* [FWARC 2008/552](http://arc.opensolaris.org/caselog/FWARC/2008/552) New Max Frame Size Property For NIU Hybrid IO

#### Niagara Crypto
* [FWARC 2006/567](http://arc.opensolaris.org/caselog/FWARC/2006/567) Niagara Crypto & RNG compatible property update
* [FWARC 2006/174](http://arc.opensolaris.org/caselog/FWARC/2006/174) NCS HV update
* [FWARC 2006/481](http://arc.opensolaris.org/caselog/FWARC/2006/481) Niagara-2 Random Number Generator API
* [FWARC 2006/567](http://arc.opensolaris.org/caselog/FWARC/2006/567) Niagara Crypto & RNG compatible property update
* [FWARC 2007/071](http://arc.opensolaris.org/caselog/FWARC/2007/071) Niagara2 Crypto Name Property Update
* [~~FWARC 2006/425~~](http://arc.opensolaris.org/caselog/FWARC/2006/425) NCS HV API Update 2
* [FWARC 2009/451](http://arc.opensolaris.org/caselog/FWARC/2009/451) NCS HV API Update 2.1
* [FWARC 2011/312](http://arc.opensolaris.org/caselog/FWARC/2011/312) Deprecate MD property "intr" on T3/T4 platforms

### Victoria Falls Platform
* [FWARC 2007/237](http://arc.opensolaris.org/caselog/FWARC/2007/237) Victoria Falls Perf Regs HV API
* [FWARC 2007/529](http://arc.opensolaris.org/caselog/FWARC/2007/529) Victoria Falls Perf Reg API Update
* [FWARC 2007/558](http://arc.opensolaris.org/caselog/FWARC/2007/558) N2/VF Random Number Generator HV API update

### Rock Platform
* [FWARC 2007/462](http://arc.opensolaris.org/caselog/FWARC/2007/462) MEM_IFLUSH Hypervisor API call
* [FWARC 2008/564](http://arc.opensolaris.org/caselog/FWARC/2008/564) MEM_IFLUSH_ALL Hypervisor API call
* [FWARC 2008/398](http://arc.opensolaris.org/caselog/FWARC/2008/398) Hypervisor API for Transactional Memory Configuration
* [FWARC 2008/399](http://arc.opensolaris.org/caselog/FWARC/2008/399) Rock Performance Counters/Samplers Hypervisor API
* [FWARC 2008/401](http://arc.opensolaris.org/caselog/FWARC/2008/401) MMU TLB page search Hypervisor API
* [FWARC 2008/592](http://arc.opensolaris.org/caselog/FWARC/2008/592) MMU_EXT API group name and number change

### KT Platform
* [FWARC 2008/613](http://arc.opensolaris.org/caselog/FWARC/2008/613) KT IOS Performance Counters API
* [FWARC 2009/434](http://arc.opensolaris.org/caselog/FWARC/2009/434) KT IOS Performance Counters API Update
* [FWARC 2008/615](http://arc.opensolaris.org/caselog/FWARC/2008/615) KT Perf Reg HV API
* [FWARC 2011/076](http://arc.opensolaris.org/caselog/FWARC/2011/076) Generalize IOS PERFREG API group and name

### VT Platform
* [FWARC 2011/009](http://arc.opensolaris.org/caselog/FWARC/2011/009) VT Performance Counters API

### Parallel Boot
* [FWARC 2009/567](http://arc.opensolaris.org/caselog/FWARC/2009/567) Parallel Boot HV APIs
* [FWARC 2009/070](http://arc.opensolaris.org/caselog/FWARC/2009/070) sun4v error report ATTR.SP_STATE
* [FWARC 2009/655](http://arc.opensolaris.org/caselog/FWARC/2009/655) sun4v error report ATTR.SP_STATE update

### Power Management
* [FWARC 2011/012](http://arc.opensolaris.org/caselog/FWARC/2011/012) CPU active power domain MD node and API

### LDoms
* [FWARC 2006/055](http://arc.opensolaris.org/caselog/FWARC/2006/055) Domain Services
* [FWARC 2006/141](http://arc.opensolaris.org/caselog/FWARC/2006/141) FMA Domain Services
* [FWARC 2006/571](http://arc.opensolaris.org/caselog/FWARC/2006/571) Corrections of LDC protocol
* [FWARC 2006/583](http://arc.opensolaris.org/caselog/FWARC/2006/583) VIO protocol updates
* [FWARC 2006/594](http://arc.opensolaris.org/caselog/FWARC/2006/594) ASR Domain Service
* [FWARC 2006/701](http://arc.opensolaris.org/caselog/FWARC/2006/701) PRI Domain Service
* [FWARC 2007/133](http://arc.opensolaris.org/caselog/FWARC/2007/133) SNMP Domain Service
* [FWARC 2007/363](http://arc.opensolaris.org/caselog/FWARC/2007/363) VIO vDisk MD node updates
* [FWARC 2007/602](http://arc.opensolaris.org/caselog/FWARC/2007/602) VIO vDisk Protocol Updates
* [FWARC 2007/672](http://arc.opensolaris.org/caselog/FWARC/2007/672) VIO vDisk protocol updates
* [FWARC 2007/671](http://arc.opensolaris.org/caselog/FWARC/2007/671) System Information Domain Services 1.0
* [FWARC 2008/016](http://arc.opensolaris.org/caselog/FWARC/2008/016) VIO vNet/vSwitch MD node updates
* [FWARC 2008/017](http://arc.opensolaris.org/caselog/FWARC/2008/017) VIO Protocol Update
* [FWARC 2008/228](http://arc.opensolaris.org/caselog/FWARC/2008/228) VIO vNet/vSwitch changes to support VLANs
* [FWARC 2008/229](http://arc.opensolaris.org/caselog/FWARC/2008/229) Virtual IO DR Domain Service
* [FWARC 2008/246](http://arc.opensolaris.org/caselog/FWARC/2008/246) Virtual IO Dynamic Device Service
* [FWARC 2008/296](http://arc.opensolaris.org/caselog/FWARC/2008/296) Crypto Unit DR Domain Service
* [FWARC 2006/184](http://arc.opensolaris.org/caselog/FWARC/2006/184) sun4v channels shared memory
* [FWARC 2008/424](http://arc.opensolaris.org/caselog/FWARC/2008/424) sun4v channels shared memory update
* [FWARC 2008/455](http://arc.opensolaris.org/caselog/FWARC/2008/455) FMA IO Domain Service
* [FWARC 2008/540](http://arc.opensolaris.org/caselog/FWARC/2008/540) Memory DR Domain Service
* [FWARC 2008/553](http://arc.opensolaris.org/caselog/FWARC/2008/553) VIO vNet/vSwitch changes to support jumbo frames
* [FWARC 2008/563](http://arc.opensolaris.org/caselog/FWARC/2008/563) Virtual Domain Service MD nodes and misc. properties
* [FWARC 2008/623](http://arc.opensolaris.org/caselog/FWARC/2008/623) Improved Error Reporting for DR Domain Services
* [FWARC 2008/696](http://arc.opensolaris.org/caselog/FWARC/2008/696) Virtual Domain Service Domain Name Properties
* [FWARC 2009/195](http://arc.opensolaris.org/caselog/FWARC/2009/195) VIO vNet/vSwitch support for physical link state information
* [FWARC 2009/452](http://arc.opensolaris.org/caselog/FWARC/2009/452) HV APIs for cooperative guest migration
* [FWARC 2009/559](http://arc.opensolaris.org/caselog/FWARC/2009/559) Domain Suspend Domain Service
* [FWARC 2009/609](http://arc.opensolaris.org/caselog/FWARC/2009/609) Direct I/O Agent
* [FWARC 2010/054](http://arc.opensolaris.org/caselog/FWARC/2010/054) VIO vNet/vSwitch support for Rx Dring Data mode
* [FWARC 2010/058](http://arc.opensolaris.org/caselog/FWARC/2010/058) Logical Domains Agent Chassis Serial Number Message
* [FWARC 2010/104](http://arc.opensolaris.org/caselog/FWARC/2010/104) Allocate LDC mapping Table
* [FWARC 2010/389](http://arc.opensolaris.org/caselog/FWARC/2010/389) Machine Description Updates for PCIe IOV
* [FWARC 2010/396](http://arc.opensolaris.org/caselog/FWARC/2010/396) Virtual PCI Proxy driver and VIO PCI Protocol
* [FWARC 2010/435](http://arc.opensolaris.org/caselog/FWARC/2010/435) VIO vSwitch update to enable/disable inter-domain network links
* [FWARC 2011/117](http://arc.opensolaris.org/caselog/FWARC/2011/117) Update to Suspend Domain Service for Cross CPU Migration
* [FWARC 2011/011](http://arc.opensolaris.org/caselog/FWARC/2011/011) PM Resource Manager Domain Service 1.0

### Trusted Platform Module
* [FWARC 2009/367](http://arc.opensolaris.org/caselog/FWARC/2009/367) HV APIs for accessing TPM registers

### Hypervisor

* [FWARC 2011/019](http://arc.opensolaris.org/caselog/FWARC/2011/019) Hypervisor Control Interface
* [FWARC 2011/024](http://arc.opensolaris.org/caselog/FWARC/2011/024) HVCTL Interface Updates for Live Migration
* [FWARC 2011/103](http://arc.opensolaris.org/caselog/FWARC/2011/103) Buffer Alignment for Live Migration HVCTL Interface
* [FWARC 2011/217](http://arc.opensolaris.org/caselog/FWARC/2011/217) hvctl protocol version number corrections

### Related
* [FWARC 2005/111](http://arc.opensolaris.org/caselog/FWARC/2005/111) Sun4v Bus Binding to Open Firmware
* FWARC 2006/276 Netra T2000 Tsalarm Service Channel
* FWARC 2006/352 Montoya IPMI service channel
* FWARC 2006/434 Third Party Remote Management Software Service Channel
* FWARC 2007/107 Update to Third Party Remote Management Software Service Channel
* [FWARC 2008/788](http://arc.opensolaris.org/caselog/FWARC/2008/788) FW Progress State Domain Service
* [FWARC 2010/150](http://arc.opensolaris.org/caselog/FWARC/2010/150) Platform Specific NIU SERDES and PHY values
* [FWARC 2011/061](http://arc.opensolaris.org/caselog/FWARC/2011/061) hv-api-groups root-node property (OBP)
