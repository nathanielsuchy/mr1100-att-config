# Mr1100 Att Config

To setup bandlocking configuration on AT&T use the following commands over telnet to your M1 MR1100 Router.

TELNET RouterIP Port 5510 (make sure USB Tethering is enabled, I usually find I have to connect over ethernet)
```
AT!GSTATUS?
AT!BAND=?
AT!BAND=03,"LTE B2/B66",0,2 
AT!BAND=04,"LTE B12",0,800 
AT!BAND=05,"LTE B14",0,2000
AT!BAND=06,"LTE B30",0,20000000
AT!BAND=07,"LTE B46",0,200000000000
```

