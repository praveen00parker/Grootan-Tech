#<?xml version="1.0" encoding="UTF-8"?>
<projectDescription>
	<name>GrootanProject</name>
	<comment></comment>
	<projects>
	</projects>
	<buildSpec>
		<buildCommand>
			<name>org.eclipse.jdt.core.javabuilder</name>
			<arguments>
			</arguments>
		</buildCommand>
		<buildCommand>
			<name>org.eclipse.wst.common.project.facet.core.builder</name>
			<arguments>
			</arguments>
		</buildCommand>
		<buildCommand>
			<name>org.eclipse.m2e.core.maven2Builder</name>
			<arguments>
			</arguments>
		</buildCommand>
		<buildCommand>
			<name>org.eclipse.wst.validation.validationbuilder</name>
			<arguments>
			</arguments>
		</buildCommand>
	</buildSpec>
	<natures>
		<nature>org.eclipse.jem.workbench.JavaEMFNature</nature>
		<nature>org.eclipse.wst.common.modulecore.ModuleCoreNature</nature>
		<nature>org.eclipse.jdt.core.javanature</nature>
		<nature>org.eclipse.m2e.core.maven2Nature</nature>
		<nature>org.eclipse.wst.common.project.facet.core.nature</nature>
		<nature>org.eclipse.wst.jsdt.core.jsNature</nature>
	</natures>
</projectDescription>
# 
<classpathentry kind="src" output="target/test-classes" path="src/test/java">
		<attributes>
			<attribute name="test" value="true"/>
			<attribute name="optional" value="true"/>
			<attribute name="maven.pomderived" value="true"/>
		</attributes>
	</classpathentry>
	<classpathentry kind="con" path="org.eclipse.m2e.MAVEN2_CLASSPATH_CONTAINER">
		<attributes>
			<attribute name="maven.pomderived" value="true"/>
			<attribute name="org.eclipse.jst.component.dependency" value="/WEB-INF/lib"/>
		</attributes>
	</classpathentry>
	<classpathentry kind="src" path="target/generated-sources/annotations">
		<attributes>
			<attribute name="ignore_optional_problems" value="true"/>
			<attribute name="optional" value="true"/>
			<attribute name="maven.pomderived" value="true"/>
			<attribute name="m2e-apt" value="true"/>
		</attributes>
	</classpathentry>
	<classpathentry kind="src" output="target/test-classes" path="target/generated-test-sources/test-annotations">
		<attributes>
			<attribute name="ignore_optional_problems" value="true"/>
			<attribute name="test" value="true"/>
			<attribute name="optional" value="true"/>
			<attribute name="maven.pomderived" value="true"/>
			<attribute name="m2e-apt" value="true"/>
		</attributes>
	</classpathentry>
	<classpathentry kind="con" path="org.eclipse.jst.server.core.container/org.eclipse.jst.server.tomcat.runtimeTarget/Apache Tomcat v8.5">
		<attributes>
			<attribute name="owner.project.facets" value="jst.web"/>
		</attributes>
	</classpathentry>
	<classpathentry kind="con" path="org.eclipse.jdt.launching.JRE_CONTAINER/org.eclipse.jdt.internal.debug.ui.launcher.StandardVMType/jdk-14.0.1">
		<attributes>
			<attribute name="module" value="true"/>
			<attribute name="owner.project.facets" value="java"/>
		</attributes>
	</classpathentry>
	<classpathentry kind="lib" path="C:/Users/Vignesh/Downloads/java-json.jar"/>
	<classpathentry kind="lib" path="C:/Users/Vignesh/Downloads/gson-2.2.2.jar"/>
	<classpathentry kind="lib" path="C:/Users/Vignesh/Downloads/json-simple-1.1.jar"/>
	<classpathentry kind="output" path="target/classes"/>
</classpath>
Grootan

<?xml version="1.0" encoding="UTF-8"?>

<project xmlns="http://maven.apache.org/POM/4.0.0" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
  xsi:schemaLocation="http://maven.apache.org/POM/4.0.0 http://maven.apache.org/xsd/maven-4.0.0.xsd">
  <modelVersion>4.0.0</modelVersion>

  <groupId>jeeva</groupId>
  <artifactId>GrootanProject</artifactId>
  <version>0.0.1-SNAPSHOT</version>
  <packaging>war</packaging>

  <name>GrootanProject Maven Webapp</name>
  <!-- FIXME change it to the project's website -->
  <url>http://www.example.com</url>

  <properties>
    <project.build.sourceEncoding>UTF-8</project.build.sourceEncoding>
    <maven.compiler.source>1.7</maven.compiler.source>
    <maven.compiler.target>1.7</maven.compiler.target>
  </properties>

  <dependencies>
    <dependency>
      <groupId>junit</groupId>
      <artifactId>junit</artifactId>
      <version>4.11</version>
      <scope>test</scope>
    </dependency>
  </dependencies>

  <build>
    <finalName>GrootanProject</finalName>
    <pluginManagement><!-- lock down plugins versions to avoid using Maven defaults (may be moved to parent pom) -->
      <plugins>
        <plugin>
          <artifactId>maven-clean-plugin</artifactId>
          <version>3.1.0</version>
        </plugin>
        <!-- see http://maven.apache.org/ref/current/maven-core/default-bindings.html#Plugin_bindings_for_war_packaging -->
        <plugin>
          <artifactId>maven-resources-plugin</artifactId>
          <version>3.0.2</version>
        </plugin>
        <plugin>
          <artifactId>maven-compiler-plugin</artifactId>
          <version>3.8.0</version>
        </plugin>
        <plugin>
          <artifactId>maven-surefire-plugin</artifactId>
          <version>2.22.1</version>
        </plugin>
        <plugin>
          <artifactId>maven-war-plugin</artifactId>
          <version>3.2.2</version>
        </plugin>
        <plugin>
          <artifactId>maven-install-plugin</artifactId>
          <version>2.5.2</version>
        </plugin>
        <plugin>
          <artifactId>maven-deploy-plugin</artifactId>
          <version>2.8.2</version>
        </plugin>
      </plugins>
    </pluginManagement>
  </build>
</project>
 Grootan-Tech
