# Installation Steps

## These are installation steps and not a user guide.

### Step 1
Download and extract SCM_Project.zip from github.
### Step 2
Download [Eclipse](http://www.eclipse.org/downloads/download.php?file=/technology/epp/downloads/release/juno/SR2/eclipse-jee-juno-SR2-win32-x86_64.zip) and unzip and open it.
### Step 3
Download [Tomcat7](https://tomcat.apache.org/download-70.cgi#7.0.81) and setup in Eclipse using new server wizard.
You may use [this tutorial](https://ibytecode.com/blog/how-to-configure-apache-tomcat-in-eclipse-ide/) to configure tomcat on eclipse.
**Perform Step 3 necessarily first and then proceed.**
### Step 4
Import SCM_Project into eclipse workspace.
### Step 5
Download [PostgreSQL](https://www.postgresql.org/download/) and [PGAdmin](https://www.pgadmin.org/download/) and setup a new database.
### Step 6
Run database scripts on PGAdmin to setup database and tables.
### Step 7
Change database connection details in database.properties file.