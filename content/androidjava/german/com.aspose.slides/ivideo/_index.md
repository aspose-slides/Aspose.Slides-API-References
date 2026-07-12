---
title: IVideo
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a video embedded into a presentation.
type: docs
url: /de/com.aspose.slides/ivideo/
---```
public interface IVideo
```

Stellt ein in eine Präsentation eingebettetes Video dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getContentType()](#getContentType--) | Gibt den MIME-Typ eines Videos zurück, codiert in (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Gibt die Kopie der Audiodaten zurück. |
| [getStream()](#getStream--) | Gibt einen Stream zum Lesen zurück. |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

Gibt den MIME-Typ eines Videos zurück, codiert in (\#getBinaryData.getBinaryData). Schreibgeschützter String.

**Rückgabe:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```

Gibt die Kopie der Audiodaten zurück. Bei großer Datenmenge sollte die Methode \#getStream.getStream in Betracht gezogen werden, um das unnötige Laden der Videodaten in den Speicher oder sogar eine OutOfMemoryException zu vermeiden. Schreibgeschütztes byte[].

**Rückgabe:**
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```

Gibt einen Stream zum Lesen zurück. Verwenden Sie 'using' oder schließen Sie den Stream nach der Verwendung.

**Rückgabe:**
java.io.InputStream - Stream zum Lesen.