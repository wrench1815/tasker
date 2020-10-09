# Tasker

**Tasker** is a Task Manager (to do Manager) to manage your tasks.

# Install

To setup **Tasker**, first install Virtual Environment and then Install requirements from `requirements.txt`.

## Setup Virtual Environment

1. `python3 -m venv venv`

   - On Linux make sure to install `python3-venv` using `apt install python3-venv`.

2. Activate Virtual Environment

   - On linux use `source ./venv/bin/activate`.

   * On Windows use `venv/Scripts/activate.ps1` for PowerShell or use `vennv/Scripts/activate.bat` for Command Prompt.

3. Update `pip` and `setuptools` using `pip install pip setuptools --upgrade`

4. Install requirements using `pip install -r requirements.txt`.

5. Run **Tasker** using `flask run`.

6. Launch Browser and head to http://localhost:5000
