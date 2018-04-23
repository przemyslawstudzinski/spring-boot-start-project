## SPRING BOOT START PROJECT

Starting project for creating spring boot applications.

### App startup
The application can be started by issuing the following command in the command line:

on mac/linux:
```bash
./gradlew clean bootRun
```
on windows:
```bash
.\gradlew clean bootRun
```
Ensure you have correct JAVA_HOME path.

## Stopping the Service
To stop the service (when it is running with `gradle bootRun`) use Control-C.


## IntelliJ Idea development
1. Install Lombok, MapStruct plugins under File -> Settings -> Plugins -> Browse repositories... search for the Lombok, MapStruct and install them all.
2. Check the Enable annotation processing checkbox under File -> Settings -> Build, Execution, Deployment -> Compiler -> Annotation Processors.
3. Download the intellij-java-google-style.xml file from the http://code.google.com/p/google-styleguide/ repo. Under 
File -> Settings -> Editor -> Code Style import the google-styleguide (gear icon -> Import Scheme -> Intellij IDEA code style XML) and choose it as current code style for the project.

## Test runs
Tests can be run by the following command in the command line:

on mac/linux:
```bash
./gradlew clean test
```
on windows:
```bash
.\gradlew clean test
```
Ensure you have correct JAVA_HOME path.
