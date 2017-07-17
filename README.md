# irkit
$ dns-sd -B _irkit._tcp
Browsing for _irkit._tcp
DATE: ---Tue 18 Jul 2017---
 0:07:00.262  ...STARTING...
Timestamp     A/R    Flags  if Domain               Service Type         Instance Name
 0:07:00.537  Add        2   4 local.               _irkit._tcp.         IRKit83F9

$ dns-sd -G v4 irkit83F9.local
DATE: ---Tue 18 Jul 2017---
 0:07:51.857  ...STARTING...
Timestamp     A/R Flags if Hostname                               Address                                      TTL
 0:07:52.058  Add     2  4 irkit83f9.local.                       192.168.3.26                                 10


curl -i "http://192.168.3.26/messages" -d '{"format":"raw","freq":38,"data":[6881,3228,1002,2368,1002,2368,1002,686,1002,686,1002,686,1002,2368,1002,686,1002,686,1002,2368,1002,2368,1002,686,1002,2368,1002,686,1002,686,1002,2368,1002,2368,1002,686,1002,2368,1002,2368,1002,686,1002,686,1002,2368,1002,686,1002,686,1002,2368,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,2368,1002,710,1002,710,1002,710,1002,710,1002,710,1002,2368,1002,2368,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,2368,1002,686,1002,686,1002,686,1002,686,1002,686,1002,2368,1002,2368,1002,686,1002,2368,1002,2368,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,2368,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,2368,1002,2368,1002,710,1002,2368,1002,710,1002,710,1002,2368,1002,2368,1002,26325,6881,3228,1002,2368,1002,2368,1002,686,1002,686,1002,686,1002,2368,1002,686,1002,686,1002,2368,1002,2368,1002,686,1002,2368,1002,686,1002,686,1002,2368,1002,2368,1002,686,1002,2368,1002,2368,1002,686,1002,686,1002,2368,1002,686,1002,686,1002,2368,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,2368,1002,686,1002,686,1002,686,1002,686,1002,686,1002,2368,1002,2368,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,2368,1002,686,1002,686,1002,686,1002,686,1002,686,1002,2368,1002,2368,1002,686,1002,2368,1002,2368,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,686,1002,2368,1002,710,1002,710,1002,710,1002,710,1002,710,1002,710,1002,710,1002,710,1002,710,1002,710,1002,710,1002,710,1002,710,1002,710,1002,710,1002,710,1002,710,1002,710,1002,710,1002,710,1002,710,1002,710,1002,710,1002,710,1002,710,1002,710,1002,710,1002,710,1002,710,1002,710,1002,710,1002,710,1002,710,1002,710,1002,710,1002,710,1002,710,1002,710,1002,710,1002,710,1002,710,1002,710,1002,710,1002,710,1002,710,1002,710,1002,710,1002,710,1002,710,1002,710,1002,710,1002,710,1002,710,1002,710,1002,710,1002,710,1002,710,1002,2368,1002,2368,1002,686,1002,2368,1002,686,1002,686,1002,2368,1002,2368,1002]}
