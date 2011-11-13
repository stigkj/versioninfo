Servlet that outputs a JSON string with version and build information


TODO

* Gradle plugin that extracts as much info from the build as possible
     * Jenkins info (build time, build nr, jenkins version)
     * VCS info (branches, tags, all commits' first row, etc)
     * JIRA info (changelog with links, look in commit message for ids)
     * look at gradle about plugin
* Maven plugin (maybe, not much fun to program)
* The servlet itself reading a specific JSON file from all jars in the webapp
     * In addition runtimne information is included (java version, IP address, etc)
* An addon that sends all this info to a ZooKeeper given an URL as a system property
