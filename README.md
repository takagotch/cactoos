### cactoos
---
https://github.com/yegor256/cactoos

http://www.cactoos.org/

```java
String text = new TextOf(
  new File("/code/a.txt")
).asString();

new LengthOf(
  new TeeInput(
    "Hello, world!",
    new File("/code/a.txt")
  )
).intValue();

byte[] data = new BytesOf(
  new ResourceOf("foo/img.jpg")
).asBytes();

String text = new FormatterdText(
  "How are you, %s?",
  name
).asString();
```

```sh
mvn clean install -Pqulice
```

```
```


