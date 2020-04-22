## Zabbix monitoring disk performance
- https://github.com/nikimaxim/zbx-disk-performance.git

### Linux Install 
#### Requirements:
- OS: RedHat family
- Zabbix-agent: 4.4 and later

#### Check bash(Out json):
- zabbix_get -s \<Host\> -k "vfs.dev.discovery"

#### Add from zabbix_agentd.conf "UserParameter" in zabbix_agentd.conf zabbix_agent:
- **github**/zabbix_agentd.conf

#### Import zabbix template:
##### For Adaptec
- **github**/Template OS Linux Disk Performance.xml

<br/>

#### Examples images:
- Graph: Read/Write sectors
![Image alt](https://github.com/nikimaxim/zbx-disk-performance/blob/master/img/1.png)

<br/>

- Graph: Utilization
![Image alt](https://github.com/nikimaxim/zbx-disk-performance/blob/master/img/2.png)

<br/>

- Discovery rules

<br/>

![Image alt](https://github.com/nikimaxim/zbx-disk-performance/blob/master/img/4.png)

<br/>

- Items prototypes

<br/>

![Image alt](https://github.com/nikimaxim/zbx-disk-performance/blob/master/img/5.png)

<br/>

- Latest data

<br/>

![Image alt](https://github.com/nikimaxim/zbx-disk-performance/blob/master/img/3.png)

<br/>

#### License
- GPL v3
