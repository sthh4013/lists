# Domain list of explict sites to block
## To use with Pihole
1. Login to the Web Admin interface: http://\<pihole IP>\/admin
1. Navigate to the AdList Group Management tab: http://\<pihole IP>\/admin/groups-adlists.php
1. Enter the blocklist URL: `https://raw.githubusercontent.com/sthh4013/lists/main/explicit.txt`
1. Update the Gravity DB
 - From Web UI: http://\<pihole IP>\/admin/gravity.php
 - From CLI: `pihole -g`
