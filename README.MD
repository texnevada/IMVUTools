# IMVU Client Tools
## __What is this for?__
I created this powershell script to make it easier to explore how the IMVU client and it's systems work

## __How do I use this program?__
1) Clone this repo into a easy to find folder
2) Open up powershell on Windows and type in the following `set-executionpolicy unrestricted` this will allow you to tune the script without issues
3) Run `imvu.ps1` and just do what it says

## __I still can't make it run what are the other things requried for this?__
- You need Python 2.7.9 because for what ever reason IMVU still uses python
- You will need an older version of click to be able to install uncompyle6 which can be downloaded using pip: `C:\Python27\python.exe -m pip install click==7.1.2`
- You need the latest uncompyle6 which can be downloaded using pip: `C:\Python27\python.exe -m pip install uncompyle6`


_Note your python27 folder must be in c:\python27 or nothing will work_
