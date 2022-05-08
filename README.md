# Backwards and Forward mouse binds for Ghidra
Based on the solution proposed in [Allow Mouse Button binds in Tool Options #208](https://github.com/NationalSecurityAgency/ghidra/issues/208). Modified to only jump between functions and not locations.

The script is tested on working on Ghidra 10.1.2

## Install
1. Copy the Java file to `$USER_HOME\ghidra_scripts\`
2. In CodeBrowser, open Script Manager (Windows -> Script Manager)
3. Click "Manage Script Directories"
4. Make sure `$USER_HOME\ghidra_scripts` is enabled
5. **Run the script**

## Notes
- Only jumps backwards/forwards between functions. Not locations
- **The script has to be run every time Ghidra boots!**