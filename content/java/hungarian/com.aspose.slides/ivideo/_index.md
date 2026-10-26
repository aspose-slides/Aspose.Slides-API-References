---
title: IVideo
second_title: Aspose.Slides for Java API Reference
description: Represents a video embedded into a presentation.
type: docs
url: /hu/com.aspose.slides/ivideo/
---```
public interface IVideo
```

A prezentációba beágyazott videót képvisel.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getContentType()](#getContentType--) | Visszaad egy videó MIME-típusát, amely a (#getBinaryData.getBinaryData) által van kódolva. |
| [getBinaryData()](#getBinaryData--) | Visszaad egy hang adatmásolatot. |
| [getStream()](#getStream--) | Visszaad egy olvasáshoz használható Stream-et. |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

Visszaad egy videó MIME-típusát, amely a (\#getBinaryData.getBinaryData) által van kódolva. Csak-olvasású String.

**Visszatér:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```

Visszaad egy hang adatmásolatot. Nagy mennyiségű adat esetén fontolja meg a \#getStream.getStream metódus használatát, hogy elkerülje a videó adatainak felesleges betöltését a memóriába, vagy akár OutOfMemoryException kivételt. Csak-olvasású byte[].

**Visszatér:**
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```

Visszaad egy olvasáshoz használt Stream-et. Használjon 'using'-et vagy zárja be a streamet a használat után.

**Visszatér:**
java.io.InputStream - Olvasáshoz használt Stream.