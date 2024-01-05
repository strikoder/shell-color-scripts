# Shell-Color-Script
Enhance your terminal experience with ShellColorScript, a collection of vibrant shell color scripts sourced from the internet. These scripts add a splash of color to your otherwise monochrome black screen.

# Installing shell-color-scripts 
To install `shell-color-scripts`, you can download the source code directly or clone the repository using git. Here are the steps:

``` bash
git clone https://github.com/Strikoder/shell-color-scripts
cd shell-color-scripts
sudo make install
```

## Removal
``` bash
sudo make uninstall
```

# Usage: colorscript [OPTION] [SCRIPT NAME/INDEX]
-h, --help, help        	Print this help.

-l, --list, list        	List all installed color scripts.

-r, --random, random    	Run a random color script.

-e, --exec, exec        	Run a specified color script by SCRIPT NAME or INDEX.

-a, --all, all          	List the outputs of all colorscripts with their SCRIPT NAME.

-b, --blacklist, blacklist	Blacklist a color script by SCRIPT NAME or INDEX.



## For even more fun, add the following line to your .bashrc or .zshrc and you will run a random color script each time you open a terminal:

``` 
colorscript random
```

### Acknowledgments: 
https://gitlab.com/dwt1/shell-color-scripts (For the makefile, most of the scripts, and support of the free software movement.)
https://github.com/joshdk (for the 'hedgehog' script.)
