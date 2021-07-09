** Run following steps **
sudo apt install python3
sudo apt install python3-pip

sudo rm /usr/bin/python
sudo ln -s /usr/bin/python3 /usr/bin/python

python -m pip install boto3
sudo rm /usr/bin/pip
sudo ln -s /usr/bin/pip3 /usr/bin/pip

sudo pip install ansible

