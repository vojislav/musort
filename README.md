# musort
shell script for sorting loose music files

# Dependencies
[mediainfo](https://mediaarea.net/en/MediaInfo)

# Configuration
Change the *musicDir* varible in the script to the full path of the directory where you want to move the files, instead of "~" use "$HOME". `$HOME/Music` for example.

# Usage
Run the script with the relative path of the directory with the music files as the argument. Mind that spaces in the filename have to be escaped with `\`. Easiest to do with tab-completion. Can be the same as *musicDir*.
