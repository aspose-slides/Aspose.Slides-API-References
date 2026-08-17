---
title: IVideo
second_title: Aspose.Slides for Java API Reference
description: Stellt ein Video dar, das in eine Präsentation eingebettet ist.
type: docs
url: /de/com.aspose.slides/ivideo/
---```
public interface IVideo
```

Stellt ein Video dar, das in eine Präsentation eingebettet ist.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getContentType()](#getContentType--) | Gibt einen MIME-Typ eines Videos zurück, codiert in (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Gibt eine Kopie der Audiodaten zurück. |
| [getStream()](#getStream--) | Gibt einen Stream zum Lesen zurück. |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```


Gibt einen MIME-Typ eines Videos zurück, codiert in (\#getBinaryData.getBinaryData). Nur-Lese String.

**Rückgabe:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```


Gibt eine Kopie der Audiodaten zurück. Bei großer Datenmenge sollte die \#getStream.getStream-Methode verwendet werden, um das unnötige Laden der Videodaten in den Speicher oder sogar eine OutOfMemoryException zu vermeiden. Nur-Lese byte[].

**Rückgabe:**
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```


Gibt einen Stream zum Lesen zurück. Verwenden Sie 'using' oder schließen Sie den Stream nach der Verwendung.

**Rückgabe:**
java.io.InputStream - Stream zum Lesen.