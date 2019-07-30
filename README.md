![SchemaCrawler](https://raw.githubusercontent.com/schemacrawler/SchemaCrawler/master/schemacrawler-distrib/src/site/resources/images/schemacrawler_logo.png) 

# SchemaCrawler Report Maven Plugin - Usage Example

> **Please see the [SchemaCrawler website](https://www.schemacrawler.com/) for more details.**

The [SchemaCrawler Report Maven Plugin](https://github.com/schemacrawler/SchemaCrawler-Report-Maven-Plugin) allows you to integrate a SchemaCrawler report of your database within the Maven-generated website for your project. Use this project to see how to use the SchemaCrawler Report Maven Plugin.

-----

## How to Use

1. Make sure [Apache Maven](https://maven.apache.org/) is installed, and on your path.
2. Open a command shell in the project directory.
3. Start the test database server.  Run `mvn antrun:run`
4. Open another command shell in the project directory.
5. Create the site with the SchemaCrawler report. Run `mvn clean site`
6. Look at the generated site in `target/site`
7. Look at `pom.xml` in the project directory for details on how to use the [SchemaCrawler Report Maven Plugin](https://github.com/schemacrawler/SchemaCrawler-Report-Maven-Plugin) 

