Simple Maven and Gradle Build Demo
=========

The source + poms are taken from the JBoss quickstart

How to build:
-------------
In the gradle directory type: 'gradle assemble' 
In the maven directory type: 'mvn install'

To deploy:
-------------
For gradle build: copy the ear gradle/ear/build/libs/ear-0.1-SNAPSHOT.ear to your deploy directory
For maven build: copy the ear ear/target/maven-ejb-in-ear.ear to your deploy directory
