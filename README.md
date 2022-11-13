# DNS

1. Domain name = rimahealth.tech
2. A record settings: name = @, value = ip address 35.223.136.105,  TTL = 7200
3. Cloud vendor used = GCP 

# Instructions for connecting Flask app to domain
1. Create VM in GCP
2. Create A record. External IP from VM. Settings above
3. Open SSH 
4. sudo apt-get update
5. sudo apt install python3-pip
6. git clone url 
7. cd into directory where app.py is
8. sudo python3 app.py
