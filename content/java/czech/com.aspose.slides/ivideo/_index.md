---
title: IVideo
second_title: Aspose.Slides for Java API Reference
description: Represents a video embedded into a presentation.
type: docs
url: /cs/com.aspose.slides/ivideo/
---```
public interface IVideo
```

Represents a video embedded into a presentation.
## Metody

| Method | Description |
| --- | --- |
| [getContentType()](#getContentType--) | Vrací MIME typ videa, zakódovaný v (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Vrací kopii dat audio. |
| [getStream()](#getStream--) | Vrací Stream stream pro čtení. |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```


Vrací MIME typ videa, zakódovaný v (\#getBinaryData.getBinaryData). Pouze pro čtení String.

**Vrací:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```


Vrací kopii dat audio. V případě velkého množství dat zvažte použití metody \#getStream.getStream, aby se zabránilo zbytečnému načítání dat videa do paměti nebo dokonce výjimce OutOfMemoryException. Pouze pro čtení byte[].

**Vrací:**
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```


Vrací Stream stream pro čtení. Použijte 'using' nebo zavřete stream po použití.

**Vrací:**
java.io.InputStream - Stream pro čtení.