# realtime-sys-mon
Real-Time Monitoring of Linux system resources and other services 

Parent Script: metrics (To run in background do nohup ./metrics &)

Add graphite config in the parent script. Parent script is responsible for spwaning for other monitoring scripts as a separate process. 

Arguments to be passed to metrics script: 

sys (Basic system monitoring - CPU, Mem, Disk I/O, Load Average) 
webapi (Nginx server monitoring)
db (MySQL DB monitoring)

