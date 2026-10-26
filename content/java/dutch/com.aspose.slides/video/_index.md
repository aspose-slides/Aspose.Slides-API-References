---
title: Video
second_title: Aspose.Slides voor de Java API-referentie
description: Stelt een afbeelding voor die in een presentatie is ingebed.
type: docs
url: /nl/com.aspose.slides/video/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IVideo](../../com.aspose.slides/ivideo), com.aspose.slides.IDOMObject
```
public class Video implements IVideo, IDOMObject
```

Stelt een afbeelding voor die in een presentatie is ingebed.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getContentType()](#getContentType--) | Retourneert een MIME-type van een video, gecodeerd in (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Retourneert een kopie van de audio-gegevens. |
| [getStream()](#getStream--) | Retourneert Stream-stream voor lezen. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getContentType() {#getContentType--}
```
public final String getContentType()
```


Retourneert een MIME-type van een video, gecodeerd in (\#getBinaryData.getBinaryData). Alleen-lezen String.

**Retourneert:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```


Retourneert een kopie van de audio-gegevens. In geval van een grote hoeveelheid gegevens overweeg het gebruik van de \#getStream.getStream-methode om onnodig laden van video-gegevens in het geheugen of zelfs een OutOfMemoryException te voorkomen. Alleen-lezen byte[].

**Retourneert:**
byte[]
### getStream() {#getStream--}
```
public final InputStream getStream()
```


Retourneert Stream-stream voor lezen. Gebruik 'using' of sluit de stream na gebruik.

**Retourneert:**
java.io.InputStream - Stream voor lezen.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Retourneert Parent_Immediate-object. Alleen-lezen IDOMObject.

**Retourneert:**
com.aspose.slides.IDOMObject