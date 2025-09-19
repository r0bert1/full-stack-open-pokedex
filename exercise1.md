Let's look at CI related questions for a web application written in Java. 

There are several tools for linting Java code. One can for example use Checkstyle for enforcing consistent coding style in combination with Spotless for automatic formatting. There are also static analysis tools like PMD and SpotBugs that can be used for detecting bugs. Additionally, there is a tool called SonarLint, which is an IDE plugin that offers linting for all the most popular programming languages, including Java of course. Lastly, the most popular Java IDEs IntelliJ IDEA, Eclipse and NetBeans all provide linting out of the box.

There are many options for testing Java code. JUnit is the most popular unit testing framework for Java projects. Spring Boot Test is a popular integration test framework for Spring based web applications written in Java.

Java is a compiled language so building a Java application entails compiling and packaging the code into an executable .jar or .war file. This can be achieved with Java package managers Gradle and Java.

GitLab has its own CI solution GitLab for GitLab projects. Other popular cloud-based options are CircleCI and Travis CI. Cloud providers Microsoft Azure, AWS and Google Cloud also offer their own CI/CD solutions.

For the Java application discussed earlier in this text, cloud-based CI makes more sense since there is only one relatively small team that uses the service. Additionally, the application is a normal web application which does not require any specialized resources that would make self-hosted CI necessary.
