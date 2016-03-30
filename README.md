# buds
Backup Ubuntu Devices Script

Backup Ubuntu based devices over ssh to a local directory.

# To run

  buds <ip address of device>

e.g.

  buds 192.168.1.20

Backs up everything in /home/phablet, and creates a list of all click packages installed.

Assumes ssh is enabled on the phone, and there is an ssh key on the phone for the machine running the backup.

TODO:

 * Calculate free space is sufficient for backup
 * Restore script
 * Optionally grab click packages from store to stash in backup
