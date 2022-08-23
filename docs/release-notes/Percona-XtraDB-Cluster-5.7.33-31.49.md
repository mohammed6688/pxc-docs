# *Percona XtraDB Cluster* 5.7.33-31.49


* **Date**

    March 22, 2021



* **Installation**

    [Installing Percona XtraDB Cluster](https://www.percona.com/doc/percona-xtradb-cluster/5.7/install/index.html)


This release fixes security vulnerability [CVE-2021-27928](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-27928), a similar issue to [CVE-2020-15180](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2020-15180)

## Bugs Fixed


* [PXC-3536](https://jira.percona.com/browse/PXC-3536): Modify processing to not allow threads/queries to be killed if the thread is in TOI


* [PXC-3565](https://jira.percona.com/browse/PXC-3565): Correct Performance of SELECT in PXC


* [PXC-3508](https://jira.percona.com/browse/PXC-3508): Explicitly set the dhparam option with socat to bypass the use of the old certs