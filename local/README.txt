#########################
# zFTPServer for Splunk #
#########################



If the location of the logs folder is not C:\Program Files\zFTPServer\log, copy the $SPLUNK_HOME/etc/apps/zftpserver/default/inputs.conf file to $SPLUNK_HOME/etc/apps/zftpserver/local/inputs.conf and adjust the location to the logs folder.  
Changes to the original application should be made in the local folder (this folder) as to prevent updates to this application from overwriting your changes.