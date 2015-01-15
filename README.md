mod-moodle
==========

Download the latest payfast moodle enrolment plugin from https://github.com/PayFast/mod-moodle/archive/master.zip

Unzip the file on your local PC and upload it to the publicly accessible Moodle installation, this should not overwrite any files on the website. [your moodle installation folder]/enrol/payfast

Login to your Moodle website as the admin, you will be presented with the 'Plugins Check' screen, press 'Update Moodle database now' button and then 'Continue'

You are now ready to insert your PayFast merchant ID and Key. Change the settings further to suite your needs, it's always advisable to do a test transaction in the Sandbox/Test site first.

Change the 'Enable PayFast Erolments' to Yes

Save your changes and go to Administration > Site administration > Plugins > Enrolments > Manage enrol plugins. Click the 'enable' icon next to the the PayFast plugin from the list.

Navigate to the specific course you're interested in charging for under from Navigation > Courses 

Once you're in the specific course, go to Administration > Users > Enrolment methods

Add PayFast as an available method from the drop down list. Add the cost (in ZAR) for the course and click 'Add method'.
