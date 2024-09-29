```
mkvirtualenv ardupilot
workon ardupilot
pip install future pexpect empy==3.3.4
./waf configure
./Tools/environment_install/install-prereqs-ubuntu.sh
./waf
```
