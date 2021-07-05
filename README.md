# Awesome Infoblox [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/seefor/awesome-infoblox)

A curated list of awesome Infoblox, libraries, software and resources.

Inspired by a lot of awesome list out there.
Credit to Sif Baksh for the original inception, John Neerdael has expanded on the list and added more useful resources.


---
### Threat Defense
* [Feed to CSP](https://github.com/njeanselme/feed-to-csp) - About
BloxOne Threat Defense integration with Fortinet and Palo Alto domain names and IPs brings an even wider IOC coverage by threat intelligence unification. Fortinet IOCs are enforced at DNS level globally on all DNS even for roaming users who have not established their VPN
* [Map endpoints to endpoint_groups based on naming policy](https://github.com/njeanselme/botdc-endpoints-management) - map endpoints to endpoint_groups based on naming policy
* [B1TD TIDE Data Feed](https://github.com/ccmarris/b1td_tide_data_feed) - Tool to easily create Threat feeds for third party solutions through Infoblox API's
* [Infoblox Threat Intelligence] (https://splunkbase.splunk.com/app/4472/) - Splunk Add-on for Infoblox Intelligence allows to get threat intelligence from Infoblox Threat Intelligence Data Exchange / TIDE (hosts/IPs/URLs - depending on your BloxOne Threat Defense license) and network intelligence from networks in NIOS IPAM. 
It optionally allows to feed Splunk Entreprise Security (Splunk ES).
* [Infoblox BloxOne Threat Defense] (https://splunkbase.splunk.com/app/4941/) - Splunk Add-on that
* - acquire BloxOne Threat Defense Cloud logs using REST API
* - filter it efficiently with full drill down support based on the time, threat property, threat class, source IP, domain name, query type 
* - summarize hits by IOCs
* - get IOCs context from Infoblox Dossier threat intelligence
* - prioritize hits based on context
* - search and pivot Threat Intelligence based on the IOCs matched in DNS traffic
* - report on BloxOne endpoints deployment

## BloxOne

*Scripts, modules and other resources*

* [python-bloxone](https://github.com/ccmarris/python-bloxone) - The Infoblox BloxOne suite of applications provides a RESTful API that is published using Swagger on [CSP](https://csp.infoblox.com/apidoc) along with other Infoblox APIs. (Author: Chris Marrison)
* [BloxOne OPH Management](https://github.com/frankhecker/infoblox-public) - Mange and rename OPH for BloxOne (Author: Franck Hecker)
* [BloxOne Ansible](https://github.com/johnneerdael/bloxone-ansible) - Infoblox Ansible Collection for BloxOne (infoblox.b1ddi_modules) allows you to interact with the BloxOne DDI through APIs. (Author: Infoblox Engineering)
* [B1DDI Automation Demo](https://github.com/ccmarris/b1ddi-automation-demo) - This script is designed to provide a standard, simple way to demonstrate the power of automation with the Bloxone DDI platform and create a set of demo data for demonstration of the GUI. (Author: Chris Marrison


#### NIOS to B1DDI
* [NIOS CSV to B1DDI](https://github.com/seefor/bloxone_ddi) - Migrate data from NIOS CSV Export to Bloxone DDI - Best option (Author: Sif Baksh) 
* [NIOS CSV to B1DDI](https://github.com/johnneerdael/csv2b1ddi) - Migrate data from NIOS CSV Export to Bloxone - Secondary option (Author: John Neerdael)


## NIOS

*Scripts, modules and other resources*

* [CSV to RPZ](https://github.com/seefor/random-scripts/tree/main/csv_to_rpz_import) - This will create an RPZ CSV file from a list of Domains in a file so you can import into NIOS
* [NIOS CSV Import](https://github.com/frankhecker/infoblox-public/tree/main/nios/csv_scripts) - This is script will help you import a CSV into NIOS and check in real time while it uploads.
* [Infoblox Ansible Modules](https://github.com/infobloxopen/infoblox-ansible) - Infoblox Ansible Collection for vNIOS allows managing your NIOS objects through APIs. It, thus, enables the DNS and IPAM automation of VM workloads that are deployed across multiple platforms. The nios_modules collection provides modules and plugins for managing the networks, IP addresses, and DNS records in NIOS. (Author: Infoblox Engineering)
* [Swagger Documentation](https://github.com/infobloxopen/infoblox-swagger-wapi) - Swagger documentation for Infoblox grid REST APIs (Author: Infoblox Engineering)
* [NIOS Zero-Touch Provisioning with Ansible](https://github.com/infobloxopen/nios-ztp-ansible) - Deploying Infoblox Grid( Grid Master and a Member) and doing initial configurations through Ansible on OpenStack. (Author: Infoblox Engineering)
* [NIOS Zero-Touch Provisioning with VMware](https://github.com/infobloxopen/vnios_ztp_vmware) - Zero touch deployment of Infoblox Grid on Vmware vsphere using Ansible (Author: Infoblox Engineering)
* [VMware Autoscale](https://github.com/infobloxopen/vmware-autoscale) - Script to automatically scale up or down the Infoblox grid, hosted on a VMWare environmen,t based on DNS queries per second (Author: Infoblox Engineering)
* [Openstack/Ansible Autoscale](https://github.com/infobloxopen/vnios-autoscale-ansible-openstack) - Autoscaling vNIOS on Openstack solution using ansible, is a combination of shell script and ansible playbook. (Author: Infoblox Engineering)
* [Terraform Provider NIOS](https://github.com/infobloxopen/terraform-provider-infoblox) - Infoblox Provider for Terraform (Author: Infoblox Engineering)


## Network Insight

*Scripts, blogs and other resources*

* [infoblox-utilities](https://github.com/infobloxopen/infoblox-utilities) - Enable discovery for networks and change networks from unmanaged to managed. (Author: Infoblox Engineering)
* [Infoblox Community](https://community.infoblox.com/t5/Network-Automation/ct-p/NetworkAutomation) - Infoblox Public Community site
* [Getting Started with 5 CCS scripts](https://community.infoblox.com/t5/How-to-Articles/5-CCS-Scripts-to-Jump-Start-Your-NetMRI-CCS-Training/ba-p/11982) - This is will get you started with Scripting language - Files can be found [here](https://community.infoblox.com/t5/Automation-Scripts/5-CCS-Scripts-to-Jump-Start-Your-NetMRI-CCS-Training/m-p/11972/highlight/true#M142)
* [Python Script getting started blog](https://community.infoblox.com/t5/Community-Blog/5-Python-Scripts-to-get-you-started-in-NetMRI/ba-p/16305) - How to use Python in NetMRI - Video can be found [here](https://community.infoblox.com/t5/Tech-Videos/A-Python-Primer-for-NetMRI-Webinar-Archive/ba-p/13956)
