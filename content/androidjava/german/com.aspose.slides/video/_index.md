---
title: Video
second_title: Aspose.Slides für Android über Java-API-Referenz
description: Stellt ein Bild dar, das in eine Präsentation eingebettet ist.
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

Stellt ein Bild dar, das in eine Präsentation eingebettet ist.
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

Gibt einen MIME-Typ eines Videos zurück, codiert in (\#getBinaryData.getBinaryData). Nur lesend String.

**Rückgabe:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

Gibt eine Kopie der Audiodaten zurück. Im Falle großer Datenmengen sollte die Methode \#getStream.getStream verwendet werden, um das unnötige Laden von Videodaten in den Speicher oder sogar eine OutOfMemoryException zu vermeiden. Nur lesend byte[].

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

Gibt das Parent_Immediate-Objekt zurück. Nur lesend IDOMObject.

**Rückgabe:**
com.aspose.slides.IDOMObject