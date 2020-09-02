# IDPASS LITE MOSIP Print Service

In `pom.xml`:

```
<repositories>
    <repository>
        <id>private-repo</id>
        <name>Private Repository</name>
        <url>https://raw.github.com/typelogic/resource/repository/</url>
        <releases>
            <enabled>true</enabled>
            <updatePolicy>never</updatePolicy>
        </releases>
        <snapshots>
            <enabled>false</enabled>
        </snapshots>
    </repository>
</repositories>

<dependencies>

    <dependency>
        <groupId>newlogic.idpass</groupId>
        <artifactId>mosip-print-idpasslite</artifactId>
        <version>1.0.0</version>
    </dependency>

    <dependency>
        <groupId>com.google.protobuf</groupId>
        <artifactId>protobuf-java</artifactId>
        <version>3.12.2</version>
    </dependency>

</dependencies>
```
