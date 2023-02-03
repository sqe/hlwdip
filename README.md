# hlwdip
homelab with dynamic ip

Exposing self hosted homelab to internet via dynamic IP.

Components :
Microk8s
Metallb -L2 networking 
Cert-manager
Helm3
Nginx ingress - deployed with hostNetwork true
Mastodon for micro blogging 

Current issues, frequent  packet drops when visiting from internet

Hosted on Thinkpad x220 laptop with Ubuntu 20.04, domain name sqapy.com is tied to public (dynamic) IP of your internet connection

![Screenshot from 2023-02-03 13-03-11](https://user-images.githubusercontent.com/503043/216710254-4ac78338-bff5-43a6-b9bb-8d8bb438f632.png)
![Screenshot from 2023-02-02 22-47-53](https://user-images.githubusercontent.com/503043/216710282-3adb70ec-80a8-462a-8e56-5eea124c1fc4.png)
![Screenshot from 2023-02-01 00-10-22](https://user-images.githubusercontent.com/503043/216710298-8e94cbc6-43af-4892-bf4c-ad6832806ceb.png)




TODO: create self servicable guide on installation and configuration!
