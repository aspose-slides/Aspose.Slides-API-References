---
title: Video
second_title: Aspose.Slides für Java API-Referenz
description: Stellt ein in eine Präsentation eingebettetes Bild dar.
type: docs
url: /de/com.aspose.slides/video/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IVideo](../../com.aspose.slides/ivideo), com.aspose.slides.IDOMObject
```
public class Video implements IVideo, IDOMObject
```

Stellt ein in eine Präsentation eingebettetes Bild dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getContentType()](#getContentType--) | Gibt einen MIME-Typ eines Videos zurück, codiert in (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Gibt eine Kopie der Audiodaten zurück. |
| [getStream()](#getStream--) | Gibt einen Stream zum Lesen zurück. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getContentType() {#getContentType--}
```
public final String getContentType()
```

Gibt einen MIME-Typ eines Videos zurück, codiert in (\#getBinaryData.getBinaryData). Nur lesbarer String.

**Rückgabe:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

Gibt eine Kopie der Audiodaten zurück. Im Falle einer großen Datenmenge sollte die Methode \#getStream.getStream verwendet werden, um das unnötige Laden von Videodaten in den Speicher oder sogar eine OutOfMemoryException zu vermeiden. Nur lesbares byte[].

**Rückgabe:**
byte[]
### getStream() {#getStream--}
```
public final InputStream getStream()
```

Gibt einen Stream zum Lesen zurück. Verwenden Sie 'using' oder schließen Sie den Stream nach der Verwendung.

**Rückgabe:**
java.io.InputStream - Stream zum Lesen.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Gibt ein Parent_Immediate-Objekt zurück. Nur lesbares IDOMObject.

**Rückgabe:**
com.aspose.slides.IDOMObject