---
title: Audio
second_title: Aspose.Slides für Java API Referenz
description: Stellt eine eingebettete Audiodatei dar.
type: docs
url: /de/com.aspose.slides/audio/
---
**Vererbung:**
java.lang.Object, com.aspose.slides.DomObject

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IAudio](../../com.aspose.slides/iaudio)
```
public class Audio extends DomObject<AudioCollection> implements IAudio
```

Stellt eine eingebettete Audiodatei dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getContentType()](#getContentType--) | Gibt einen MIME-Typ eines Audios zurück, codiert in (\#getBinaryData.getBinaryData). |
| [setContentType(String value)](#setContentType-java.lang.String-) | Gibt einen MIME-Typ eines Audios zurück, codiert in (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Gibt eine Kopie der Audiodaten zurück. |
| [getStream()](#getStream--) | Gibt einen Stream zum Lesen zurück. |
### getContentType() {#getContentType--}
```
public final String getContentType()
```

Gibt einen MIME-Typ eines Audios zurück, codiert in (\#getBinaryData.getBinaryData). Nur-Lese-String.

**Rückgabe:**
java.lang.String
### setContentType(String value) {#setContentType-java.lang.String-}
```
public final void setContentType(String value)
```

Gibt einen MIME-Typ eines Audios zurück, codiert in (\#getBinaryData.getBinaryData). Nur-Lese-String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

Gibt eine Kopie der Audiodaten zurück. Bei großen Datenmengen sollte die Methode \#getStream.getStream in Betracht gezogen werden, um das unnötige Laden von Audiodaten in den Speicher oder sogar eine OutOfMemoryException zu vermeiden. Nur-Lese-Byte[].

**Rückgabe:**
byte[]
### getStream() {#getStream--}
```
public final InputStream getStream()
```

Gibt einen Stream zum Lesen zurück. Verwenden Sie 'using' oder schließen Sie den Stream nach der Benutzung.

**Rückgabe:**
java.io.InputStream - Stream zum Lesen.