---
title: IAudio
second_title: Aspose.Slides for Java API Reference
description: Represents an embedded audio file.
type: docs
url: /de/com.aspose.slides/iaudio/
---```
public interface IAudio
```

Stellt eine eingebettete Audiodatei dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getContentType()](#getContentType--) | Gibt einen MIME-Typ einer Audiodatei zurück, codiert in (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Gibt eine Kopie der Audiodaten zurück. |
| [getStream()](#getStream--) | Gibt einen Stream zum Lesen zurück. |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

Gibt einen MIME-Typ einer Audiodatei zurück, codiert in (\#getBinaryData.getBinaryData). Nur-Lesen String.

**Rückgabe:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```

Gibt eine Kopie der Audiodaten zurück. Im Falle einer großen Datenmenge sollte die Methode \#getStream.getStream verwendet werden, um das unnötige Laden der Audiodaten in den Speicher oder sogar eine OutOfMemoryException zu vermeiden. Nur-Lesen byte[].

**Rückgabe:**
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```

Gibt einen Stream zum Lesen zurück. Verwenden Sie 'using' oder schließen Sie den Stream nach der Verwendung.

**Rückgabe:**
java.io.InputStream - Stream zum Lesen.