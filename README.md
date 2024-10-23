# AIXUN T3x updater

This tool allows updating of AiXun T3A/T3B/T320/T420D without installing their vendor software or sign-up.

# Original repo

This is a copy of the original repo by *Michael Niewöhner* (c0d3z3r0)

I made this copy because I don't like to modify the phython environment on my computer (iMac).
The t3xupdate.py program is modified so it uses a python *Virtual Environment* (**venv**) in which 
libraries are loaded. After using the program the *venv* is automatically deleted.

# Instructions:

1. Get firmware image either from [aixun-updates.github.io](https://aixun-updates.github.io) or like this `wget https://usr.tnyzeq.icu/~dd/aixun-updates/firmware/JC_M_T3A_1.36.bin`
2. ~~Install dependencies: `pip install -r requirements.txt`~~ (not needed anymore)
3. Connect your soldering station via USB
4. Run the updater: `python3 t3xupdate.py JC_M_T3A_1.xx.bin`

## License

Copyright (c) 2024 Michael Niewöhner

This is open source software, licensed under GPLv2. See LICENSE file for details.
