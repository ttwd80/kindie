Step 01 - Skeleton
===

1. Ensure you have maven `3.6.3` installed by running `mvn --version`.
2. Ensure you have JDK 11 installed by running `javac --version`.
3. Run this command `mvn archetype:generate`
4. You will see `Choose a number or apply filter (format: [groupId:]artifactId, case sensitive contains): 1594:`
   1. Type in `1599`.
5. You will get this: `Choose org.apache.maven.archetypes:maven-archetype-webapp version:`
6. Type in `7`.
7. For `Define value for property 'groupId':`, type in a groupId value. This can be anything. I will be using `com.github.ttwd80`.
8. For `Define value for property 'artifactId':` type in `kindie`.
9.  For `Define value for property 'version' 1.0-SNAPSHOT:`, press <kbd>Enter</kbd> 
10. For `Define value for property 'package'`, type in groupId + artifactId. In my case: `com.github.ttwd80.kindie`.
11. For `Confirm properties configuration:`, press <kbd>Enter</kbd> .
12. Type `cd kindie`.
13. Type `mvn clean test`.
14. You should see `[INFO] BUILD SUCCESS` in the last few lines of the output.
15. Done with skeleton