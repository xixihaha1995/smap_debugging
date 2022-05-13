# Files and Documentation

[Google Code Archive - Long-term storage for Google Code Project Hosting.](https://code.google.com/archive/p/smap-data/downloads)

git@github.com:SoftwareDefinedBuildings/smap.git

git@github.com:immesys/powerdb2.git

git@github.com:stevedh/readingdb.git

[sMAP: the Simple Measurement and Actuation Profile — sMAP 2.0 documentation (pythonhosted.org)](https://pythonhosted.org/Smap/en/2.0/index.html)

# Commands

```shell
find / -type d -name 'httpdocs'
find . -name "foo*"
```

# Procedures

## Ubuntu 20.04 -> Failed

```py
virtualenv venv --python=python2.7
```

 pip install smap

## Ubuntu 11.10 -> Cannot install this OS

docker pull lpenz/ubuntu-oneiric-amd64-minbase

[Index of /releases/11.10 (ubuntu.com)](http://old-releases.ubuntu.com/releases/11.10/)

# Ubutun 14.04

[Install Python 2.7.14 on Ubuntu 14.04 (github.com)](https://gist.github.com/pigeonflight/39e7513e46b419b8b51f8671445c4ea2)

```shell
sudo apt-get update
sudo apt-get install build-essential checkinstall -y
sudo apt-get install libreadline-gplv2-dev libncursesw5-dev libssl-dev libsqlite3-dev tk-dev libgdbm-dev libc6-dev libbz2-dev -y
cd /usr/src
sudo wget https://www.python.org/ftp/python/2.7.14/Python-2.7.14.tgz
sudo tar xzf Python-2.7.14.tgz
cd Python-2.7.14
sudo ./configure --enable-optimizations
sudo make install
```



[How to Install Pip on Ubuntu 14.04 LTS - Liquid Web](https://www.liquidweb.com/kb/how-to-install-pip-on-ubuntu-14-04-lts/)

```shell
curl "https://bootstrap.pypa.io/get-pip.py" -o "get-pip.py"
python get-pip.py
```



pip install virtualenv

virtualenv smap_env

pip install smap

git clone git@github.com:xixihaha1995/sources.git

sudo apt-get install monit

```shell
#uncommented
set httpd port 2812 and
    use address localhost
    allow localhost
```

sudo /etc/init.d/monit restart

sudo apt update

sudo apt install software-properties-common

```
sudo add-apt-repository ppa:stevedh/smap
sudo apt-get update
sudo apt-get install readingdb readingdb-python

$ sudo monit reload
$ sudo monit start readingdb
```

```
apt-get install postgresql postgresql-contrib python-psycopg2

sudo systemctl start postgresql.service
```