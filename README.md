# mkvalidator v0.6.0
mkvalidator linux scan release needed for some ftpd (drftpd)

SOURCE for build, looks on --> https://github.com/Matroska-Org/foundation-source

# SETUP TO USER
- unzip the *.zip file to /home/YOURUSERS/

+ SET mkvalidator (DEFiNiTELY METHOD) **<- APPROUVE**
- nano ~/.profile
+ ADD of the BOTTOM **($home = /home/YOURUSERS/)**
  - export MKVALIDATOR="$HOME/mkvalidator"
  - export PATH="$MKVALIDATOR:$PATH"
- RELOGiN to SSH and TRY **mkvalidator**
