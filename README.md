#bennu-tools

This is a set of bash functions that will help you when working with bennu modules.

##dependencies
* realpath (sudo apt-get install realpath)

##configuration of .bennu_profile
* WORKSPACE_DIR - directory where the checkedout repositories are
* LOG - directory when mvn output will be dumped
* APP - name of the webapp deployed at tomcat

##usage
`source .bennu_profile`

##list of bash functions
* goto \<module-name\> - cd to the directory with \<module-name\>. bash-completion available.
* cptom - copies current module target/*.jar to APP
* dodeps - compiles current module and all dependencies
* doall - compiles all modules at WORKSPACE_DIR

##examples





