# vivek-repo
 #!/bin/bash

# Script: create_backup.sh

DATE=$(date +%F)
FOLDER="backup_$DATE"

mkdir -p $FOLDER
touch $FOLDER/log_$DATE.txt

echo "Backup folder & log file created at $FOLDER/"

