This is Maven repository for my projects.

To add this repository to your Maven project, add the following lines to your pom.xml or settings.xml file:

   <repositories>
      <repository>
         <id>vorburger-releases</id>
         <url>http://vorburger.github.com/m2p2-repository/maven/releases</url>
      </repository>
      <repository>
         <id>vorburger-snapshots</id>
         <url>http://vorburger.github.com/m2p2-repository/maven/snapshots</url>
      </repository>
   </repositories>

To create your own maven repo read posts such as:
* http://blog2.vorburger.ch/2013/08/deploying-github-hosted-maven-incl.html
* http://chkal.blogspot.com/2010/09/maven-repositories-on-github.html
* http://ananthakumaran.in/2010/04/03/github-mavenized.html
* http://www.jroller.com/mrdon/entry/maven_enabled_project_hosting_with
* http://cemerick.com/2010/08/24/hosting-maven-repos-on-github/

See https://github.com/vorburger/mvnDeployGitHubTravisCI for my example project how to publish a GitHub project to a repo like this one via https://Travis-ci.org
