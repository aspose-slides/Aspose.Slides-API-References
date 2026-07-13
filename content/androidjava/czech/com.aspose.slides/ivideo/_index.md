---
title: IVideo
second_title: Aspose.Slides pro Android pomocí Java API Reference
description: Představuje video vložené do prezentace.
type: docs
url: /cs/com.aspose.slides/ivideo/
---```
public interface IVideo
```

Představuje video vložené do prezentace.
## Metody

| Metoda | Popis |
| --- | --- |
| [getContentType()](#getContentType--) | Vrací MIME typ videa, zakódovaný v (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Vrací kopii dat audia. |
| [getStream()](#getStream--) | Vrací Stream pro čtení. |
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

Vrací kopii dat audia. V případě velkého množství dat zvažte použití metody \#getStream.getStream, aby se zabránilo zbytečnému načítání dat videa do paměti nebo dokonce výjimce OutOfMemoryException. Pouze pro čtení byte[].

**Vrací:**
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```

Vrací Stream pro čtení. Použijte 'using' nebo uzavřete stream po použití.

**Vrací:**
java.io.InputStream - Stream pro čtení.