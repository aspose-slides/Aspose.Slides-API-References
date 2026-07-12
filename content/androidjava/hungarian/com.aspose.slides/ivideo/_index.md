---
title: IVideo
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a video embedded into a presentation.
type: docs
url: /hu/com.aspose.slides/ivideo/
---```
public interface IVideo
```

Egy a prezentációba beágyazott videót képvisel.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getContentType()](#getContentType--) | Returns a MIME type of an video, encoded in (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Returns the copy of an audio's data. |
| [getStream()](#getStream--) | Returns Stream stream for reading. |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

Visszaadja a videó MIME típusát, kódolva a (\#getBinaryData.getBinaryData) segítségével. Csak olvasható String.

**Visszatér:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```

Visszaadja a hang adatmásolatát. Nagy mennyiségű adat esetén fontolja meg a \#getStream.getStream metódus használatát, hogy elkerülje a videó adatának felesleges betöltését a memóriába vagy akár OutOfMemoryException-t. Csak olvasható byte[].

**Visszatér:**
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```

Visszaadja a Stream stream-et olvasáshoz. Használja a 'using' konstrukciót vagy zárja be a stream-et a használat után.

**Visszatér:**
java.io.InputStream - Stream for reading.