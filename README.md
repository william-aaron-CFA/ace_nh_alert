This repository contains the ace_nh_viol.py alert script which emails an alert if the ACE satellite does not record qualifying electron or proton data for eight hours.
The alert sends after 8 hours by default, however the script can be called with arguements to change the amount of time before alerting to any number between 1 and 12 hours.

cron job

testing
scrapper as waaron

3,8,13,18,23,28,33,38,43,48,53,58 * * * * /home/waaron/git/ace_nh_alert/ace_nh_viol.py

implementation
cronjob unecessary as it will run with the ace_main_script call
