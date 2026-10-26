---
title: Video
second_title: Aspose.Slides Androidra a Java API hivatkozással
description: Egy prezentációba beágyazott képet reprezentál.
type: docs
url: /hu/com.aspose.slides/video/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IVideo](../../com.aspose.slides/ivideo), com.aspose.slides.IDOMObject
```
public class Video implements IVideo, IDOMObject
```

Egy prezentációba beágyazott képet reprezentál.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getContentType()](#getContentType--) | Visszaadja egy videó MIME-típusát, amely a (\#getBinaryData.getBinaryData) metódusban van kódolva. |
| [getBinaryData()](#getBinaryData--) | Visszaadja egy hang adatának másolatát. |
| [getStream()](#getStream--) | Visszaad egy Stream-et olvasásra. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getContentType() {#getContentType--}
```
public final String getContentType()
```


Visszaadja egy videó MIME-típusát, amely a (\#getBinaryData.getBinaryData) metódusban van kódolva. Csak olvasható String.

**Visszaadja:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```


Visszaadja egy hang adatának másolatát. Nagy mennyiségű adat esetén érdemes a \#getStream.getStream metódust használni, hogy elkerüljük a videó adatainak felesleges memóriába töltését vagy akár OutOfMemoryException-t. Csak olvasható byte[].

**Visszaadja:**
byte[]
### getStream() {#getStream--}
```
public final InputStream getStream()
```


Visszaad egy Stream-et olvasásra. Használja a 'using'-et vagy zárja be a stream-et a használat után.

**Visszaadja:**
java.io.InputStream - Olvasásra szolgáló Stream.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Visszaad egy Parent_Immediate objektumot. Csak olvasható IDOMObject.

**Visszaadja:**
com.aspose.slides.IDOMObject