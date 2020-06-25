# Shodan_search_terms
This is a collection of shodan searches I used over the years.
I have some comments in the of lines, (using -) don't use it in the search.

ICS:
title:sensor
realm="Westermo MRD-310" (admin/westermo)
title:scada
Schneider
title:"ICT Protege WX&reg;"
ACTL
title:elvaco - sweeden
"authentication enabled" port:"4800" 
title:"NPort Web Console"
"Simatic" - (siemens SIMATIC S7 HMI)
"Siemens" AG
http.favicon.hash:-1051205943 - (Simatic 1200 Siemens)
http.favicon.hash:661304498 - (scalance siemens switch)



Fuel: 
"Morrison Bros. Co."

BMS: (building management system)
html:"Carel pCOWeb Home Page"
html:"remote control" html:Kieback
title:struxureware
html:"Building Operation WebStation"
html:"Climatix"

MEDICAL:
"Content-Length: 1804" "Server: Apache-Coyote/1.1" ---- ge mri login page
MEDWEB-AUTH
surgery country:"US"
html:Technomogies -  ge login page
title:"Login | PACS WebAdmin"
title:"CARESTREAM SOLUTIONS"
dicom
medisoft
title:"iConnect® Access"
html:AMICAS
html:meddream

printers:
title:printer
Server: Virata-EmWeb/R6_2_1 - HP
Server: debut/1.20 - brother
Server: CANON HTTP Server - canon
canon 
lexmark
"27 Feb 1972 08:00:00 GMT" - lexmark/Dell

tv:
hostname: tv
product:samsung

web- cameras:
title:camera
"Server: IQinVision Embedded 1.0"
title:surveillance
Server: DVRDVS-Webs -hikvision
Server: App-webs/ - hikvision
Server: BBVS/ - spy camera
title:dvr
html:"DVR"
html:"network camera"
"DCS-" / product:"*webcam" -multiple D-link versions of  IP-camera
title:web client port:8334
Server: OwnServer1.0 
Server: U S Software Web
yawcam
Android Webcam Server -Authenticate
Server: i-Catcher Console
ADH-web
Server: VB100
Auther: Steven Wu
title:'+tm01+'
D-Link Internet Camera 200
imagiatek ipcam (admin/)
Server: VCS-VideoJet-Webserver
Boa ipcam (admin/123456)
hikvision Content-Length: 1341 (admin/12345)
"webcam" "last-modified"
Content-Length: 695 (root/pass)
title:"NetCamXL"
title:"WVC210 Wireless-G PTZ Internet Camera with Audio"
d-Link Internet Camera, 200 OK
title:"DCS-5300G" Server: D-Link Internet Camera
title:"Login cgicc form" (admin/)
LNE3003 Wireless IP Camera (admin/admin)
title:"DCS-5220 IP camera"
title:"Web Viewer for Samsung DVR" Content-Length: 2524 (admin/4321)
title:"IP CAMERA Viewer" Content-Length: 703
webcamxp
webcam 7
IPCamera_Logo (admin/admin)
Vivotek Network Camera -401
Server: SQ-WEBCAM (admin/admin)
abelcam
onvif://www.onvif.org - /xml that related to chinese DVR firm
html:GetCommercialName()

unknown IoT:
title:AVtech - avtech monitoring sensor
Server: thttpd/ - many kinds of IoT (light http server)
title:unitronics
title:'login to ICC pro' - water farm system
title: Central unit - somfy
Server: MisterHouse
docsis
Server: IS2 Web Server 2.07
Server: Apache/2.4.7 (Ubuntu) country:"IL" "Content-Length: 281-4"
title:"sunny webbox"
Server: Boa/
title:"solar-log"
port:1883
title:LG
product:LG
title:hms power (canada)
welcome to fridge (telnet)
title:"Loxone Smart Home"
title:cve-30360
title:"web client"
UPS_Server/1.0


routers:
title:myhome
product:"micro_httpd"
Oct 1968 12:00:00 GMT -title:"Mon Modem" -title:"NUMERICABLE"
title:TL 
title: ::: ACEmanager ::: 
Server: router
Server: ADB Broadband HTTP Server 
title:mx230 - malaysia cellular router
title:'+home_42+'  - - belkin
title:"Login unifi controller"
Server: lighttpd/1.4.35 PHPSESSID Cache-Control: max-age=180000
title:cisco
Oct 1968 12:00:00 GMT  -title:"Mon Modem" -title:"NUMERICABLE"
Netgear
Router Webserver - TP-Link
401 NG - D-Link
title:Comcast
title:"Device configuration"
eHTTP v2.0 - procurve
"title: Connect WAN 3G" -"Set-Cookie: " - Digi (default open)
"title: Connect WAN 3G" - Digi (password protect)
title:":::AceManager:::" - sierra router

Firewall:
html:juniper
html:fortigate

VPN:
"Firmware: 1 Hostname: local"

port:161 -router -RouterOS -Cisco -Wireless -DOCSIS -SonicWALL -Linux -HP -Brother -apple -Lantronix -websensor -crestron -epson -PROCURVE -netopia -ricoh -Xerox -dell

Applications:
title:GitLab
title:jenkins
title:rancher
title:zabbix http.favicon.hash:892542951
title:solarwinds
title:kibana
product:elastic
http.favicon.hash:-43161126 (slack)
http.favicon.hash:927199499 (box)
html:"prtg network"

VoIP:
product:"Polycom SoundPoint VoIP phone http config"

general:
has_screenshot:true -port:5900 -port:5901 -port:6000
title:"Projector LAN Control"
Bentlor
