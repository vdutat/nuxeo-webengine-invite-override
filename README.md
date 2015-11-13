# About feature
 
This is a sample `Web Engine` module overriding `Nuxeo User WebEngine Invite` module. It changes the background image of the HTML page inviting the user to enter his/her password.

This module is **not** supported by Nuxeo.

* Project status: prototype
 
# Building
 
        mvn clean install
  
## QA
  
None.
 
## Deploying

2 options:

- copy the JAR bundle in `$NUXEO_HOME/templates/custom/bundles/` and activate the `custom` template (see Nuxeo documentation [Configuration Templates](https://doc.nuxeo.com/display/ADMINDOC/Configuration+Templates)).
- **OR** copy the JAR bundle in `$NUXEO_HOME/nxserver/plugins/` or `$NUXEO_HOME/nxserver/bundles/`

Then restart the server.

