# Centralized Infrastructure Monitoring with Zabbix



Academic cybersecurity project.



This project implements a centralized monitoring solution using Zabbix.



## Technologies



- Zabbix 7.4

- Zabbix Agent 2

- Docker

- Docker Compose

- Ubuntu Server

- MySQL

- VMware Workstation

- Gmail SMTP

- Microsoft Teams

- Power Automate



## Architecture



Two Ubuntu Server virtual machines were used.



Zabbix-Server hosts MySQL, Zabbix Server and Zabbix Web with Docker Compose.



Ubuntu-Client is monitored using Zabbix Agent 2.



## Monitoring



CPU, RAM, disk, network and agent availability are monitored.



Triggers detect incidents and actions send notifications by email and Microsoft Teams.



## Validation



The solution was tested by stopping Zabbix Agent 2 on the monitored client.



Zabbix detected the incident, generated a problem and sent notifications.



After restarting the agent, the problem was recovered.



## Security



Sensitive credentials and webhook URLs are not included in this repository.
