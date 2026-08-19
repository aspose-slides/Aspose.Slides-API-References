---
title: IAudio
second_title: Aspose.Slides for Java API Reference
description: Reprezentuje vložený zvukový soubor.
type: docs
url: /cs/com.aspose.slides/iaudio/
---```
public interface IAudio
```

Reprezentuje vložený zvukový soubor.
## Metody

| Method | Description |
| --- | --- |
| [getContentType()](#getContentType--) | Vrací MIME typ zvuku, zakódovaný v (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Vrací kopii dat zvukového souboru. |
| [getStream()](#getStream--) | Vrací Stream stream pro čtení. |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

Vrací MIME typ zvuku, zakódovaný v (\#getBinaryData.getBinaryData). Pouze pro čtení String.

**Vrací:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```

Vrací kopii dat zvukového souboru. V případě velkého množství dat zvažte použití metody \#getStream.getStream, aby se předešlo zbytečnému načítání dat zvuku do paměti nebo dokonce OutOfMemoryException. Pouze pro čtení byte[].

**Vrací:**
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```

Vrací Stream stream pro čtení. Použijte 'using' nebo po použití uzavřete stream.

**Vrací:**
java.io.InputStream - Stream pro čtení.