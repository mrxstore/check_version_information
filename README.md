# check_version_information

## Description  
`check_version_information` is a utility (library/script) designed to check and manage software version information. It allows easy retrieval, comparison, and display of application or library versions, helping automate update processes and ensure compatibility.

## Features  
- Retrieve the current version of an application or module  
- Compare versions (e.g., semantic versioning)  
- Check if an update is available  
- Support for various version formats (e.g., `1.2.3`, `v2.0-beta`)  
- Integration with CI/CD systems for automated version control

## Installation  
```bash
pip install check_version_information
```
or
Simply copy the check_version_information.py file into your project.

Usage Example
```bash
from check_version_information import VersionChecker

checker = VersionChecker(current_version="1.4.2", latest_version="1.5.0")

if checker.is_update_available():
    print("A new version is available!")
else:
    print("You have the latest version.")
```

Requirements

・Python 3.6+
・No additional dependencies (or list if any)

License
MIT
