Spark11HDP2.1
=============

This page contains details of running Hortonworks 2.1 VM with Spark

Download
===========

https://www.dropbox.com/s/ovlbo8gh5a4lm1d/hdpspark.ova?dl=0


Steps
=========
a) Import the hdpspark.ova file into your VM Containers

b) Start it up

c) The startup page should show details on the VM and how to log in


Directories and URL
================
Login as "root"

Spark
======
Spark is set in the path.
---------------------------------------------
[root@sandbox ~]# ls -l
total 4
lrwxrwxrwx 1 root root   59 Sep 27 06:54 spark -> /root/Spark11/spark-1.1.0.2.1.5.0-695-bin-2.4.0.2.1.5.0-695
drwxr-xr-x 3 root root 4096 Sep 27 06:51 Spark11
lrwxrwxrwx 1 root root   48 Apr 22 07:13 start_ambari.sh -> /usr/lib/hue/tools/start_scripts/start_ambari.sh
lrwxrwxrwx 1 root root   47 Apr 22 07:13 start_hbase.sh -> /usr/lib/hue/tools/start_scripts/start_hbase.sh

To run the spark Shell

[root@sandbox ~]# spark-shell
----------------------------------------------

Hortonworks URL
================
HUE
http://172.16.154.167:8000/about/





