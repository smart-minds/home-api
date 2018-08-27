# Developing on Linux
# Install the core dependencies.

```shell
sudo apt-get install python3-pip python3-dev python3-venv
```

# In order to run script/setup below you will need some more dependencies.

```shell
sudo apt-get install libssl-dev libxml2-dev libxslt1-dev libjpeg-dev libffi-dev libudev-dev zlib1g-dev
git clone https://github.com/smartminds/home-api.git
cd home-api
```

# Setting up virtual environment

# To isolate your environment from the rest of the system, set up a venv. Within the home-api directory, create and activate your virtual environment.

```shell
python3 -m venv .
source bin/activate
```

# Install the requirements with a provided script named setup.

```shell
script/setup
```

# Run the application
```shell
hass --open-ui --config ./configuration/
```