SrMonitor
=========
A simple django demo

This project will try to build a simple node monitor, to monitor the CPU usage, memory usage, network IO and disk storage.

It will base on Django and bootstrap and mysql.

All the node data collected by a python agent and send to the server. The server store all data to mysql. User can watch the statistics from the web page to see whether the nodes monitored are healthy.

Scope of Version 0.1: 1. Only collect user CPU usage; 2. The web page only show curve of user CPU usage;
