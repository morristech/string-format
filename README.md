# Usage

```java
Strings.format("Hello {firstname} {lastname}!")
	.with("firstname", "John")
	.with("lastname", "Doe")
	.build();
```

# Get it

[Download JAR](http://search.maven.org/remotecontent?filepath=com/joanzapata/utils/string-format/1.0.0/string-format-1.0.0.jar) or via **Maven Central**

```xml
<dependency>
    <groupId>com.joanzapata.utils</groupId>
    <artifactId>string-format</artifactId>
    <version>1.0.0</version>
</dependency>
```

# License

```
Copyright 2013 Joan Zapata

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
``