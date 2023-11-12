# Python back-end for the weatherapp
## Installation
* Dependencies
  * Docker
  * Python

* Clone the git repo
```sh
$ git clone https://github.com/phaeseval/weather-app-python-backend
```

### Docker <span style="color:red">(!!currently broken)</span>

* To install in a docker container run: 
```sh
$ docker build -t <image-name> .
```

* Run the docker container with:
```sh
$ docker run -p 5000:5000 <image-name>
```

### Local Installation
* Create a python-env to avoid breaking your system:
```sh
$ python -m venv .
```
* Install dependencies on requirements.txt:
```sh 
$ .venv/bin/python -m pip install -r requirements.txt
```
* Run the `main.py`:
```sh
$ .venv/bin/python main.py
```
<p>By default you can access the web app by visiting the <a> localohst:5000 </a> on your web browser</p>

## Todo
- [ ] Fix Docker file