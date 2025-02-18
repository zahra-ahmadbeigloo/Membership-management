# Membership Management 
## Overview
Membership-Management is a Python project designed to manage membership records by generating and cleaning membership files. This project includes a script to generate mock data for members and transfer inactive members to a separate file for better organization. The repository demonstrates basic programming concepts and file handling in Python.

## Features
- Generate Membership Data: Creates a file with mock data for members, including membership number, date joined, and active status.

- Clean Membership Data: Separates active and inactive members into different files for easier management.

## Code Explanation
### Generate Files
The `genFiles` function generates two files: one for current members (members.txt) and one for inactive members (inactive.txt).

### Clean Files
The `cleanFiles` function reads the current members file, identifies inactive members, and appends them to the inactive members file while removing them from the current members file.

## Example Output

### Active Members

| Membership No | Date Joined | Active |
|---------------|-------------|--------|
| 12345         | 2020-01-01  | yes    |
| 67890         | 2019-12-31  | yes    |
| ...           | ...         | ...    |

### Inactive Members

| Membership No | Date Joined | Active |
|---------------|-------------|--------|
| 54321         | 2018-05-15  | no     |
| 98765         | 2017-06-20  | no     |
| ...           | ...         | ...    |

## Requirements

Python 3.x 

## License

This project is licensed under the MIT License.

## Contributing
Feel free to fork this repository, make enhancements, and submit pull requests. Contributions and suggestions are welcome!

