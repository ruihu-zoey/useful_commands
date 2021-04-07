# my useful commands notebook
## Copy folders form server to mac/server
### i. From Linux to Mac (run from the Linux machine):

scp -r filename.txt user@remote_server:/Users/YOURNAME/
### ii. From Linux to Mac (run from the Mac):

scp -r user@remote_server:/Users/YOURNAME/filename.txt .