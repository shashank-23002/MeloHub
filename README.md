# MeloHub

This is a collaborative full stack web-application built using Django , ReactJs , MaterialUI , SpotifyAPI.

## Setup Instructions

### Install Required Python Modules

```bash
pip install -r requirements.txt
```
Make sure to install requests module
```bash
pip install requests
```
### Start Web Server

To start the web server you need to run the following sequence of commands.

Install virtualenv (if not already installed):
```bash 
pip install virtualenv
```
Create a Virtual Environment:
```bash 
virtualenv myenv
```
Activate the Virtual Environment:
```bash 
source myenv/bin/activate - For Mac
myenv\Scripts\activate - For Windows
```
Enter into your desired folder
```bash 
cd "MeloHub"
```
Next run the django web server.
```bash
python manage.py runserver
```
For Mac Users make sure to convert - 
```bash
pip - pip3
python - python3
```


### [Install Node.js](https://nodejs.org/en/)

### Install Node Modules

First cd into the ```frontend``` folder.
```bash
cd frontend
```
Next install all dependicies.
```bash
npm i
```
You may also need to install `nvm` to handle correct node version - 
```bash
nvm insall < Node version >
```

### Compile the Front-End

Run the production compile script
```bash
npm run build
```
or for development:
```bash
npm run dev
```