---
title: Video
second_title: Aspose.Slides voor Android via Java API-referentie
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
| [getContentType()](#getContentType--) | Geeft een MIME-type van een video terug, gecodeerd in (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Geeft een kopie van de gegevens van een audio terug. |
| [getStream()](#getStream--) | Geeft een Stream voor lezen terug. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getContentType() {#getContentType--}
```
public final String getContentType()
```

Geeft een MIME-type van een video terug, gecodeerd in (\#getBinaryData.getBinaryData). Alleen-lezen String.

**Retourwaarde:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

Geeft een kopie van de gegevens van een audio terug. In het geval van een grote hoeveelheid gegevens moet u overwegen de \#getStream.getStream-methode te gebruiken om onnodig laden van videogegevens in het geheugen of zelfs een OutOfMemoryException te voorkomen. Alleen-lezen byte[].

**Retourwaarde:**
byte[]
### getStream() {#getStream--}
```
public final InputStream getStream()
```

Geeft een Stream voor lezen terug. Gebruik 'using' of sluit de stream na gebruik.

**Retourwaarde:**
java.io.InputStream - Stream voor lezen.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Geeft een Parent_Immediate-object terug. Alleen-lezen IDOMObject.

**Retourwaarde:**
com.aspose.slides.IDOMObject