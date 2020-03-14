# liquibase-changeset-generate

Steps to generate liquibase changeset from database:

1. Download liquibase tar.gz file from - https://download.liquibase.org/liquibase-pro-trial-request-form/ by registering. You will get licenseKey
2. Extract tar.gz file 
3. Download postgresql driver jar and copy it to extracted folder
4. Create liquibase.properties in extracted folder
5. Add following properties in liquibase.properties file
changeLogFile: dbchangelog.xml
driver: org.postgresql.Driver
url: jdbc:postgresql://localhost:5432/postgres
username: username
password: password
referenceDriver: org.postgresql.Driver
referenceUrl: "jdbc:postgresql://localhost:5432/postgres"
referencePassword: passw
liquibaseProLicenseKey: ABwwGgQUBpb7UdwwhN
classpath: postgresql-42.2.11.jar 
