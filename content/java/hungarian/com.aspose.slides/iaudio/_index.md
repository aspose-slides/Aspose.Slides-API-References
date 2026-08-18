---
title: IAudio
second_title: Aspose.Slides for Java API Reference
description: Beágyazott hangfájl képviselője.
type: docs
url: /hu/com.aspose.slides/iaudio/
---```
public interface IAudio
```

Beágyazott hangfájl képviselője.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getContentType()](#getContentType--) | Visszaad egy hang MIME típusát, amely a (\#getBinaryData.getBinaryData) metódusban van kódolva. |
| [getBinaryData()](#getBinaryData--) | Visszaad egy másolatot a hang adatáról. |
| [getStream()](#getStream--) | Visszaad egy Stream-et olvasáshoz. |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

Visszaadja egy hang MIME típusát, amely a (\#getBinaryData.getBinaryData) metódusban van kódolva. Írásvédett String.

**Visszatér:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```

Visszaad egy másolatot a hang adatáról. Nagy mennyiségű adat esetén fontolja meg a \#getStream.getStream metódus használatát, hogy elkerülje a hang adatának felesleges betöltését a memóriába, vagy akár OutOfMemoryException kivételt. Írásvédett byte[].

**Visszatér:**
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```

Visszaad egy Stream-et olvasáshoz. Használja a 'using' kulcsszót, vagy zárja be a stream-et a használat után.

**Visszatér:**
java.io.InputStream - Stream for reading.