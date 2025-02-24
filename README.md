# Shodan Dorks
*Dorks for shodan.io* website. Taken from publicly available sources.

# Shodan
_Shodan is a search engine that lets the user find specific types
of computers (webcams, routers, servers, etc.) connected to the internet using a variety of filters._

## Basic Shodan Filters
### city:
Find devices in a particular city.<br/>
`city:"Bangalore"`

### country:
Find devices in a particular country.<br/>
`country:"IN"`

### geo:
Find devices by giving geographical coordinates.<br/>
`geo:"56.913055,118.250862"`

### hostname:
Find devices matching the hostname.<br/>
`server: "gws" hostname:"google"`

### net:
Find devices based on an IP address or /x CIDR.<br/>
`net:210.214.0.0/16`

### os:
Find devices based on operating system.<br/>
`os:"windows 7"`

### port:
Find devices based on open ports.<br/>
`proftpd port:21`

### before/after:
Find devices before or after between a given time.<br/>
`apache after:22/02/2009 before:14/3/2010`

### Citrix:
Find Citrix Gateway.<br/>
`title:"citrix gateway"`

### Wifi Passwords:
Helps to find the cleartext wifi passwords in Shodan.</br>
`html:"def_wirelesspassword"`

### Surveillance Cams:
With username:admin and password: :P</br>
`NETSurveillance uc-httpd`

### Fuel Pumps connected to internet:
No auth required to access CLI terminal.</br>
`"privileged command" GET`

### Windows RDP Password:
But may contain secondary windows auth</br>
`"\x03\x00\x00\x0b\x06\xd0\x00\x00\x124\x00"`

### Mongo DB servers:
It may give info about mongo db servers and dashboard </br>
`"MongoDB Server Information" port:27017 -authentication`

### FTP servers allowing anonymous access:
Complete Anon access </br>
`"220" "230 Login successful." port:21`

### Jenkins:
Jenkins Unrestricted Dashboard </br>
`x-jenkins 200`

### Hacked routers:
Routers which got compromised </br>
`hacked-router-help-sos`

### Open ATM:
May allow for ATM Access availability </br>
`NCR Port:"161"`

### Telnet Access:
NO password required for telnet access. </br>
`port:23 console gateway`

### Misconfigured Wordpress Sites:
The wp-config.php if accessed can give out the database credentials. </br>
`http.html:"* The wp-config.php creation script uses this file"`

### Hiring:
Find sites hiring. </br>
`"X-Recruiting:"`

### Android Root Bridge:
Find android root bridges with port 5555. </br>
`"Android Debug Bridge" "Device" port:5555`

### Etherium Miners:
Shows the miners running ETH. </br>
`"ETH - Total speed"`

### Tesla Powerpack charging Status:
Helps to find the charging status of tesla powerpack. </br>
`http.title:"Tesla PowerPack System" http.component:"d3" -ga3ca4f2`




### YOU CAN ALSO COMBINE FILTERS TO MAKE INTO ADVANCED FILTERS FOR QUICK RECON.


<h3>Changes</h3>
<table border="1">
<tr><th>Change Description</th><th>Date</th></tr>
<tr><td style='color: #34;'>Update version- 2025-01-16 11:15:32</td><td>2025-01-16 11:15:32</td></tr>
</table>
<h3>Changes</h3>
<table border="1">
<tr><th>Change Description</th><th>Date</th></tr>
<tr><td style='color: #36;'>Update version- 2025-01-16 11:16:06</td><td>2025-01-16 11:16:06</td></tr>
</table>
<h3>Changes</h3>
<table border="1">
<tr><th>Change Description</th><th>Date</th></tr>
<tr><td style='color: #32;'>Update version- 2025-01-23 16:10:36</td><td>2025-01-23 16:10:36</td></tr>
</table>
<h3>Changes</h3>
<table border="1">
<tr><th>Change Description</th><th>Date</th></tr>
<tr><td style='color: #31;'>Update version- 2025-01-23 16:15:48</td><td>2025-01-23 16:15:48</td></tr>
</table>
<h3>Changes</h3>
<table border="1">
<tr><th>Change Description</th><th>Date</th></tr>
<tr><td style='color: #32;'>Update version- 2025-01-23 16:19:54</td><td>2025-01-23 16:19:54</td></tr>
</table>
<h3>Changes</h3>
<table border="1">
<tr><th>Change Description</th><th>Date</th></tr>
<tr><td style='color: #34;'>Update version- 2025-02-10 16:55:18</td><td>2025-02-10 16:55:18</td></tr>
</table>
<h3>Changes</h3>
<table border="1">
<tr><th>Change Description</th><th>Date</th></tr>
<tr><td style='color: #35;'>Update version- 2025-02-10 16:56:30</td><td>2025-02-10 16:56:30</td></tr>
</table>
<h3>Changes</h3>
<table border="1">
<tr><th>Change Description</th><th>Date</th></tr>
<tr><td style='color: #31;'>Update version- 2025-02-11 02:15:29</td><td>2025-02-11 02:15:29</td></tr>
</table>
<h3>Changes</h3>
<table border="1">
<tr><th>Change Description</th><th>Date</th></tr>
<tr><td style='color: #35;'>Update version- 2025-02-19 16:43:44</td><td>2025-02-19 16:43:44</td></tr>
</table>
<h3>Changes</h3>
<table border="1">
<tr><th>Change Description</th><th>Date</th></tr>
<tr><td style='color: #33;'>Update version- 2025-02-20 17:38:49</td><td>2025-02-20 17:38:49</td></tr>
</table>
<h3>Changes</h3>
<table border="1">
<tr><th>Change Description</th><th>Date</th></tr>
<tr><td style='color: #35;'>Update version- 2025-02-20 19:52:40</td><td>2025-02-20 19:52:40</td></tr>
</table>
<h3>Changes</h3>
<table border="1">
<tr><th>Change Description</th><th>Date</th></tr>
<tr><td style='color: #35;'>Update version- 2025-02-20 19:58:53</td><td>2025-02-20 19:58:53</td></tr>
</table>
<h3>Changes</h3>
<table border="1">
<tr><th>Change Description</th><th>Date</th></tr>
<tr><td style='color: #34;'>Update version- 2025-02-20 20:00:39</td><td>2025-02-20 20:00:39</td></tr>
</table>
<h3>Changes</h3>
<table border="1">
<tr><th>Change Description</th><th>Date</th></tr>
<tr><td style='color: #35;'>Update version- 2025-02-20 20:02:05</td><td>2025-02-20 20:02:05</td></tr>
</table>
<h3>Changes</h3>
<table border="1">
<tr><th>Change Description</th><th>Date</th></tr>
<tr><td style='color: #33;'>Update version- 2025-02-21 10:05:07</td><td>2025-02-21 10:05:07</td></tr>
</table>
<h3>Changes</h3>
<table border="1">
<tr><th>Change Description</th><th>Date</th></tr>
<tr><td style='color: #34;'>Update version- 2025-02-23 13:28:41</td><td>2025-02-23 13:28:41</td></tr>
</table>
<h3>Changes</h3>
<table border="1">
<tr><th>Change Description</th><th>Date</th></tr>
<tr><td style='color: #34;'>Update version- 2025-02-24 15:01:18</td><td>2025-02-24 15:01:18</td></tr>
</table>
<h3>Changes</h3>
<table border="1">
<tr><th>Change Description</th><th>Date</th></tr>
<tr><td style='color: #35;'>Update version- 2025-02-24 15:02:36</td><td>2025-02-24 15:02:36</td></tr>
</table>
