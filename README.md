# Versions Maven Plugin version-rules.xml

A curated list of rules for the Versions Maven Plugin that excludes any non-release artifacts.

## Usage

```
<plugin>
    <groupId>org.codehaus.mojo</groupId>
    <artifactId>versions-maven-plugin</artifactId>
    <version>${versions-maven-plugin.version}</version>
    <configuration>
        <generateBackupPoms>false</generateBackupPoms>
        <rulesUri>https://raw.githubusercontent.com/movewp3/version-rules/version-rules.xml</rulesUri>
    </configuration>
</plugin>
```
