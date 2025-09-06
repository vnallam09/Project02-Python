# Project02-Python

A Python utility for automated folder creation and organization.

## Features

- Create folders for a range of years (2020-2023)
- Create data folders from lists (csv, excel, json)
- Create prefixed output folders
- Create periodic folders with timestamps
- Create standardized region folders (with options for lowercase and space removal)

## Requirements

- Python 3.x
- Required packages are listed in requirements.txt

## Usage

Run the main script:

```bash
python teja_project_setup.py
```

The script will create various folder structures and log its actions to `project.log`.

## Author

Venkat Teja Nallamothu (September 2025)

### Git commands
* git add . 
* git commit -m '<commit message>'
* git push 

### python run commands
* to create an venv in vs code use (Ctrl+Shift+P) to get command pallet and select 'Python: Create Environment...'
* to activate it use interminal > ./.venv/Scripts/activate
* to install dependencies run   > pip install -r .\requirements.txt
* finally to run the python script use > py teja_project_setup.py 