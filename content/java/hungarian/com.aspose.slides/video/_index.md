---
title: Video
second_title: Aspose.Slides Java API referencia
description: Egy bemutatóba ágyazott képet képvisel.
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

Egy bemutatóba ágyazott képet képvisel.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getContentType()](#getContentType--) | Visszaad egy videó MIME-típust, amely a (\#getBinaryData.getBinaryData) kódban van kódolva. |
| [getBinaryData()](#getBinaryData--) | Visszaad egy hang adatmásolatát. |
| [getStream()](#getStream--) | Visszaad egy Stream-folyamot olvasáshoz. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getContentType() {#getContentType--}
```
public final String getContentType()
```


Visszaad egy videó MIME-típust, amely a (\#getBinaryData.getBinaryData) kódban van kódolva. Csak olvasható String.

**Visszatér:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```


Visszaad egy hang adatmásolatát. Nagy mennyiségű adat esetén fontoljuk meg a \#getStream.getStream metódus használatát, hogy elkerüljük a videó adatainak felesleges betöltését a memóriába vagy akár OutOfMemoryException kivételt. Csak olvasható byte[].

**Visszatér:**
byte[]
### getStream() {#getStream--}
```
public final InputStream getStream()
```


Visszaad egy Stream-folyamot olvasáshoz. Használjon 'using'-et, vagy zárja be a folyamot a használat után.

**Visszatér:**
java.io.InputStream - Olvasáshoz használható folyam.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Visszaad egy Parent\_Immediate objektumot. Csak olvasható IDOMObject.

**Visszatér:**
com.aspose.slides.IDOMObject