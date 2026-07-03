# Week 2 - Cloud Computing (AWS EC2)

## Project: The Server Commander

### Objective
Launch an Ubuntu EC2 instance, connect using SSH, install Apache Web Server, and host a custom "Welcome to DecodeLabs" webpage.

## Tools Used
- AWS EC2
- Ubuntu Server
- EC2 Instance Connect
- Apache2

## Commands Used

```bash
sudo apt update
sudo apt upgrade -y
sudo apt install apache2 -y
echo "<h1>Welcome to DecodeLabs</h1><p>Hosted by Riya on AWS EC2</p>" | sudo tee /var/www/html/index.html
sudo systemctl restart apache2
```

## Result
Successfully launched an EC2 instance, installed Apache, and hosted a custom web page on AWS.
