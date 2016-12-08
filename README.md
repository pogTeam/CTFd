![](https://raw.githubusercontent.com/pogTeam/CTFd/master/CTFd/static/original/img/logo.png)
====

CTFd is a CTF in a can. Easily modifiable and has everything you need to run a jeopardy style CTF.

## Installation

### On MAC OS X

Make sure the following packets are installed
```bash
brew install libffi python
```

Now we need to install the virtualenv
```bash
pip install virtualenv
```

Now let's clone the repository
```bash
git clone https://github.com/pogTeam/CTFd.git
```

Now let's access the CTFd directory
```bash
cd CTFd
```

Now we need to create the virtualenv base
```bash
virtualenv --python=python2.7 venv
```

Now let's activate the environment
```bash
source venv/bin/activate
```

Now we need to install the requirements
```bash
pip install -r requirements.txt
```

You can configure the CTFd in [CTFd/config.py](https://github.com/pogTeam/CTFd/blob/master/CTFd/config.py) as you like.

The last step is to run the server
```bash
python serve.py
```

Now you need to access the CTFd on your browser in: http://127.0.0.1:4000


## Default Installation by isislab
Install:
 1. `./prepare.sh` to install dependencies using apt.
 2. Modify [CTFd/config.py](https://github.com/isislab/CTFd/blob/master/CTFd/config.py) to your liking.
 3. Use `python serve.py` in a terminal to drop into debug mode.
 4. [Here](https://github.com/isislab/CTFd/wiki/Deployment) are some deployment options



# Live Demo:
- [https://demo.ctfd.io/](https://demo.ctfd.io/)
- Logo by [Laura Barbera](http://www.laurabb.com/)
- Theme by [Christopher Thompson](https://github.com/breadchris)

# Original Repo
- [isislab](https://github.com/isislab/CTFd) 
