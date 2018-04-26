===========================================README=========================================

1. Install squid 
apt-get update
sudo apt-get install squid

2. start squid at startup
cp ./tools/systemd/squid.service /etc/systemd/system/
systemctl enable squid

3. configuration
make a copy of config file (/etc/squid/squid.conf)
do necessary changes to squid.config according to example squid.conf files in this
git repo.
