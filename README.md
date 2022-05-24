BambooL [![BambooL Build Status](https://img.shields.io/github/workflow/status/sizquirt/BambooL/Build%20BambooL/master)](https://github.com/sizquirt/BambooL/actions)

===========

Performance focused paper fork with slight modifications.

How To (Server Admins)
------
Wait for release.

Download coming soon.. 

Go to PaperMC for a working jar while this is being worked on.

How To (Plugin Developers)
------
 * See our API patches [here](patches/api)
 * (Paper API) See upcoming, pending, and recently added API [here](https://github.com/PaperMC/Paper/projects/6)
 * Paper/BambooL API javadocs here: [papermc.io/javadocs](https://papermc.io/javadocs/)
 * Maven Repo (for paper-api):
```xml
<repository>
    <id>papermc</id>
    <url>https://repo.papermc.io/repository/maven-public/</url>
</repository>
```
 * Artifact Information:
```xml
<dependency>
    <groupId>io.papermc.paper</groupId>
    <artifactId>paper-api</artifactId>
    <version>1.18.2-R0.1-SNAPSHOT</version>
    <scope>provided</scope>
</dependency>
 ```


How To (Compiling Jar From Source)
------
To compile BambooL, you need JDK 17 (or 18) and an internet connection.

Clone this repo, run `./gradlew applyPatches`, then `./gradlew createReobfBundlerJar` from your terminal. You can find the compiled jar in the project root's `build/libs` directory.

To get a full list of tasks, run `./gradlew tasks`.

How To (Pull Request)


Special Thanks To:
-------------
[![Paper](https://www.github.com/PaperMC/Paper/

[![YourKit-Logo](https://www.yourkit.com/images/yklogo.png)](https://www.yourkit.com/)

[YourKit](https://www.yourkit.com/), makers of the outstanding java profiler, support open source projects of all kinds with their full featured [Java](https://www.yourkit.com/java/profiler) and [.NET](https://www.yourkit.com/.net/profiler) application profilers. We thank them for granting Paper an OSS license so that we can make our software the best it can be.

[<img src="https://user-images.githubusercontent.com/21148213/121807008-8ffc6700-cc52-11eb-96a7-2f6f260f8fda.png" alt="" width="150">](https://www.jetbrains.com)

[JetBrains](https://www.jetbrains.com/), creators of the IntelliJ IDEA, supports Paper with one of their [Open Source Licenses](https://www.jetbrains.com/opensource/). IntelliJ IDEA is the recommended IDE for working with Paper, and most of the Paper team uses it.


