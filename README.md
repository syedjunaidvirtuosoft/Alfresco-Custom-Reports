# User-Access-Rights-Reports
This add-on contains a separate Surf Page which lists Sites, Users and data associated with it in a Tabular Format.
The Report lists the following entries.
* Sites
* Users on Site
* Users Role on Site
* Folders on Site
* Permission on Folders

Note that the report lists folders only with <b>Uninherited Permissions</b>
You can Search and Filter data by searching Site Name or Username or both Site Name & Username.
To access the report there is a <b>Dropdown</b> on the header of Alfresco Home Page.
Report is developed and tested on Alfresco 6 Community Version (Docker Based) but works on Alfresco versions.

# Deployment:
* Place the <b>useraccessrights-platform-1.0-SNAPSHOT.amp</b> in /usr/local/tomcat/amps.
* Install the amp through alfresco-mmt.jar. " <b>java -jar /usr/local/tomcat/alfresco-mmt/alfresco-mmt*.jar install  /usr/local/tomcat/amps/useraccessrights-platform-1.0-SNAPSHOT.amp /usr/local/tomcat/webapps/alfresco -nobackup -force</b> "
* Place the <b>useraccessrights-share-1.0-SNAPSHOT.amp</b> in /usr/local/tomcat/amps_share.
* Install the amp through alfresco-mmt.jar. " <b>java -jar /usr/local/tomcat/alfresco-mmt/alfresco-mmt*.jar install  /usr/local/tomcat/amps_share/useraccessrights-share-1.0-SNAPSHOT.amp /usr/local/tomcat/webapps/share -nobackup -force</b> "
* Restart your Alfresco Services.
* After restarting your Alfresco services login with Admin user and redirect to the report by clicking on the <b>Site User Access Report</b> on the dropdown at the Homepage.

# Preview:

