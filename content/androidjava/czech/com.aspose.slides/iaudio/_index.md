---
title: IAudio
second_title: Aspose.Slides pro Android přes Java API Reference
description: Reprezentuje vložený zvukový soubor.
type: docs
url: /cs/com.aspose.slides/iaudio/
---```
public interface IAudio
```

Reprezentuje vložený zvukový soubor.
## Metody

| Metoda | Popis |
| --- | --- |
| [getContentType()](#getContentType--) | Vrací MIME typ zvuku, kódovaný v (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Vrací kopii dat zvuku. |
| [getStream()](#getStream--) | Vrací Stream stream pro čtení. |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

Vrací MIME typ zvuku, kódovaný v (\#getBinaryData.getBinaryData). Jen pro čtení String.

**Vrací:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```

Vrací kopii dat zvuku. V případě velkého množství dat zvažte použití metody \#getStream.getStream, aby se předešlo zbytečnému načítání dat zvuku do paměti nebo dokonce výjimce OutOfMemoryException. Jen pro čtení byte[].

**Vrací:**
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```

Vrací Stream stream pro čtení. Použijte 'using' nebo po použití stream zavřete.

**Vrací:**
java.io.InputStream - Stream pro čtení.