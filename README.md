# Sunset-Midnight-Ctf-Walkthrough :sunrise_over_mountains:
Today we are going to solve another boot2root challenge called “Sunset: Midnight”.  It’s available at VulnHub for penetration testing and you can download it from here. The credit for making this lab goes to whitecr0wz. Let’s get started and learn how to successfully break it down.<br>

Level: Intermediate<br>

## Penetration Testing Methodology<br>

### Reconnaissance<br>
:sunglasses:Nmap<br>

### Enumeration<br>
Hydra bruteforce MySQL service<br>

### Exploiting<br>
WordPress administrator’s password change<br>
Modification of code to build a webshell<br>

### Privilege Escalation<br>
:sunglasses:Misuse of recycled passwords<br>
:sunglasses:Binary abuse without fixed load path<br>
:sunglasses:Capture the flag

### Usage !!
:ghost: With the use of nmap 
#### -sn 192.168.0/24
we first see the networks connected to the host. It is basically a ping scan<br>
:ghost: After we get the vm's ip(the vulnerable machine) we perform an aggressive scan with 
#### nmap -A
:ghost: After that, We add the IP address and the “sunset-midnight” host to our “/etc/hosts” as indicated by the creator of the machine in the description. Like in my case:
#### 192.168.43.91    sunset-midnight
:ghost: Then we enumerate the target and see that its in Wordpress

### Rest details you can see from the docs provided !!

### Thank you !! :pray:
## Enjoy :hugs:
