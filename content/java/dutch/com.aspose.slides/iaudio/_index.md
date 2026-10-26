---
title: IAudio
second_title: Aspose.Slides for Java API Reference
description: Represents an embedded audio file.
type: docs
url: /nl/com.aspose.slides/iaudio/
---```
public interface IAudio
```

Stelt een ingesloten audio-bestand voor.
## Methoden

| Methode | Omschrijving |
| --- | --- |
| [getContentType()](#getContentType--) | Retourneert een MIME-type van een audio, gecodeerd in (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Retourneert een kopie van de data van een audio. |
| [getStream()](#getStream--) | Retourneert Stream stream voor lezen. |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```


Retourneert een MIME-type van een audio, gecodeerd in (\#getBinaryData.getBinaryData). Alleen-lezen String.

**Retourneert:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```


Retourneert een kopie van de data van een audio. In geval van een grote hoeveelheid data kunt u overwegen de \#getStream.getStream-methode te gebruiken om onnodig laden van audio-data in het geheugen of zelfs OutOfMemoryException te voorkomen. Alleen-lezen byte[].

**Retourneert:**
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```


Retourneert Stream stream voor lezen. Gebruik 'using' of sluit de stream na gebruik.

**Retourneert:**
java.io.InputStream - Stream for reading.