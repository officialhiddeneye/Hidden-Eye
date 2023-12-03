## Hidden-Eye Setup
                                                                                        This script automates the installation process for Hidden-Eye, installing necessary packages and dependencies on Termux.
                                                                                        ### Installation Steps
1. Run the script using `./setup.sh`.
2. Packages and dependencies will be installed automatically.
3. Hidden-Eye files will be organized and configured for use.
                                                                                        ### Dependencies Installed
- [pv](https://www.ivarch.com/programs/pv.shtml): Pipe Viewer for enhanced package installation display.                                                                        - [python](https://www.python.org/): Programming language used for scripting.
- [cmatrix](https://github.com/abishekvashok/cmatrix): Terminal-based "Matrix" animation.                                                                                       - [figlet](http://www.figlet.org/): Tool for creating ASCII text banners.               - [ruby](https://www.ruby-lang.org/): Programming language used for certain functionalities.                                                                                    - [mpv](https://mpv.io/): Multimedia player for playing sound effects.
- [termux-api](https://wiki.termux.com/wiki/Termux:API): Termux API for interacting with the Termux environment.
                                                                                        ### Usage
1. Run the `setup.sh` script to install packages and dependencies.
2. Hidden-Eye files are copied to the appropriate directories.
3. `login.sh` is executed to set up the customized login system.
                                                                                        ### Note                                                                                - The script assumes the existence of specific sound files (`Access-Granted.mp3`, `Jarvis2.mp3`, `JARVIS.mp3`) and a Python script (`sound_effect.py`), which are moved to the `Song` directory.
- The `network.py` script is moved to the `NETWORK` directory.

### Files Moved
- `login.sh`: Customized login script.
- `delete.sh`: Cleanup script (assumed to be present in the `Hidden-Eye` directory).
- `setup.sh`: Setup script for automating installation.
- `sound_effect.py`: Python script for playing sound effects.
- `banner.sh`: ASCII art banner script.

### Credits
This script is part of the Hidden-Eye project.

### Author
- **Author Name**: ℠S̶͌𝖍𝖚𝖇𝖍𝖆𝖒༎ຶ‿༎ຶ 𝕽𝖆𝖓𝖆**

### License
This script is licensed under the [MIT License](LICENSE).

### Contact
For issues and suggestions, contact the author at shubhamhacker4322@gmail.com.
~
