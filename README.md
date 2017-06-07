# Home Automation
Home automation control for ac outlets, lights, temperature, etc. 
Webpage control is based upon this https://github.com/vartan/pi-remote.git

## Setup

### Packages
```bash
sudo apt-get install tmux
```

### Node
1) Get Node
	+ Download lates NODE ARM6 for Raspberry Pi 1B or ARM7 for Pi 2 and 3 from [NodeJS](https://nodejs.org/en/download/) 
	+ Or use included tarball downloaded 07.06.2017 for Pi1
2) Install Node
```bash
# Unzip: 
tar -xvf node-v*
# Enter folder: 
cd node-v*
# Install:
sudo cp -R * /usr/local/
```

### Files
No files change yet

### Setup server environment
```bash
cd webserver
npm install
```

## Run the webserver
```bash
sudo node webserver/app.js
```
