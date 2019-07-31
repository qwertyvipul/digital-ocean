# digital-ocean
Tips &amp; tricks for getting along DigitalOcean

## Getting started

### Create non-root sudo user
First thing first - you do not want to use your root account! Create a non-root superuser
```bash
# add a new user to your system
adduser username

# add the user to the sudo group
usermod -aG sudo username

# switch to the new user account
su - username
```

```bash
sudo apt-get update
sudo apt-get upgrade
```

### Installing node
```bash
su root
apt install node
apt install npm
```

## Important Links
1. https://www.wikihow.com/Uninstall-Ubuntu-Software
