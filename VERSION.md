v0.0.9
---------------------------
Forgot the delete tag on the backup cleanup cron. 

v0.0.8
---------------------------
Updated cleanup cron to correctly find and remove old backups.

v0.0.7
---------------------------
Updated backup script to use temp dir for directories and to create a tar.

v0.0.6
---------------------------
Significant overhaul of the backup process. Before we had unnecessary support
for backing up to an alternate location and syncing to a backup target,
but this isn't appropriate to handle in the role itself. The new process is
much simpler.

Also made changes to the collectd receiver, which is disabled by default now.

v0.0.5
---------------------------
Removing support for cent6, as snmpcollector does not support cent6

v0.0.4
---------------------------
Actually installs the snmpcollector rpm now. previously this was a manual
step because it isn't in an RPM repo anywhere at the moment.

v0.0.3
---------------------------
Fixed Cent6 compatibility issues

v0.0.2
---------------------------
Added support for authentication

v0.0.1
---------------------------
Initial Commit - working version
