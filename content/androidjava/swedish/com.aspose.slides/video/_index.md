---
title: Video
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en bild inbäddad i en presentation.
type: docs
url: /sv/com.aspose.slides/video/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IVideo](../../com.aspose.slides/ivideo), com.aspose.slides.IDOMObject
```
public class Video implements IVideo, IDOMObject
```

Representerar en bild inbäddad i en presentation.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getContentType()](#getContentType--) | Returnerar en MIME-typ för en video, kodad i (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Returnerar en kopia av ljudets data. |
| [getStream()](#getStream--) | Returnerar Stream för läsning. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getContentType() {#getContentType--}
```
public final String getContentType()
```


Returnerar en MIME-typ för en video, kodad i (\#getBinaryData.getBinaryData). Skrivskyddad String.

**Returnerar:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```


Returnerar en kopia av ljudets data. Vid stora mängder data bör du överväga att använda \#getStream.getStream-metoden för att förhindra onödig laddning av videons data i minnet eller till och med ett OutOfMemoryException. Skrivskyddad byte[].

**Returnerar:**
byte[]
### getStream() {#getStream--}
```
public final InputStream getStream()
```


Returnerar Stream för läsning. Använd 'using' eller stäng strömmen efter användning.

**Returnerar:**
java.io.InputStream - Stream för läsning.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Returnerar Parent_Immediate-objektet. Skrivskyddad IDOMObject.

**Returnerar:**
com.aspose.slides.IDOMObject