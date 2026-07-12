---
title: IAudio
second_title: Aspose.Slides for Android via Java API Reference
description: Stellt eine eingebettete Audiodatei dar.
type: docs
url: /de/com.aspose.slides/iaudio/
---```
public interface IAudio
```

Stellt eine eingebettete Audiodatei dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getContentType()](#getContentType--) | Gibt einen MIME-Typ eines Audios zurück, codiert in (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Gibt eine Kopie der Audiodaten zurück. |
| [getStream()](#getStream--) | Gibt Stream stream zum Lesen zurück. |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```


Gibt einen MIME-Typ eines Audios zurück, codiert in (\#getBinaryData.getBinaryData). Schreibgeschützter String.

**Returns:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```


Gibt eine Kopie der Audiodaten zurück. Im Falle großer Datenmengen sollten Sie die Methode \#getStream.getStream in Betracht ziehen, um das unnötige Laden der Audiodaten in den Speicher oder sogar eine OutOfMemoryException zu vermeiden. Schreibgeschütztes byte[].

**Returns:**
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```


Gibt Stream stream zum Lesen zurück. Verwenden Sie 'using' oder schließen Sie den Stream nach dem Gebrauch.

**Returns:**
java.io.InputStream - Stream for reading.