Openapi Maven Repository
========

This contains recent versions of the openapi jars for use with maven. To use these in one of your plugins add this to your pom.xml:
```
<repositories>
	<repository>
		<id>vektah-openapi</id>
		<name>3rd party openapi repository</name>
		<url>https://github.com/Vektah/maven-intellij-openapi/raw/master/</url>
	</repository>
</repositories>

<dependencies>
	<dependency>
		<scope>provided</scope>
		<groupId>net.vektah</groupId>
		<artifactId>intellij-openapi</artifactId>
		<version>12.1.4</version>
	</dependency>
	<dependency>
		<scope>provided</scope>
		<groupId>net.vektah</groupId>
		<artifactId>intellij-util</artifactId>
		<version>12.1.4</version>
	</dependency>
	<dependency>
		<scope>provided</scope>
		<groupId>net.vektah</groupId>
		<artifactId>intellij-annotations</artifactId>
		<version>12.1.4</version>
	</dependency>
	<dependency>
		<groupId>net.vektah</groupId>
		<scope>provided</scope>
		<artifactId>intellij-extensions</artifactId>
		<version>12.1.4</version>
	</dependency>
</dependencies>
```


The files hosted here have been taken from the Intellij Community distribution, you can find out more at http://www.jetbrains.org/display/IJOS/Home
